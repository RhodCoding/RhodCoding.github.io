<script>
  import "../app.css"; // Import global styles

  let isOpen = false; // State for toggling the menu

  const toggleMenu = () => {
      isOpen = !isOpen; // Toggle the isOpen state
  };
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet"> 
</svelte:head>

<main> <!-- Navigation -->
  <nav>
      <h1>portfolio</h1>
      <button class="toggle-button" on:click={toggleMenu}>
        ☰
      </button>
      <ul class="{isOpen ? 'open' : ''}"> <!-- Apply 'open' class when isOpen is true -->
          <li><a href="/">home</a></li>
          <li><a href="/portfolio">portfolio</a></li>
          <li><a href="/about">about</a></li>
          <li><a href="/contact">contact</a></li>
      </ul>
      <a href="https://github.com/RhodCoding" class="git">Github</a>
  </nav>
  <slot></slot>
</main>

