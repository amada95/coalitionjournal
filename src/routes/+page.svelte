<script>
  let showMenu = false;

  function toggleNavbar() {
    showMenu = !showMenu;
  }
</script>

<div>
  <div>
    <nav class="navbar">
      <div class="container">
        <a href="/">
			<img href="%sveltekit.assets%/images/logo/logo_horizontal.png" alt="Coalition Journal Logo" />
        </a>
        <div onclick={toggleNavbar} class="hidden">
          <button type="button" class="menubutton">
			button
		  </button>
        </div>
      </div>

      <div class="{showMenu ? 'flex' : 'hidden'}">
        <a class="home" href="/">Home</a>
        <a class="about" href="/about">About Us</a>
      </div>
    </nav>
  </div>
</div>

<style>
	.navbar {
		display: flex;
	}
	.container {
		display: flex;
		justify-items: center;
	}
</style>
