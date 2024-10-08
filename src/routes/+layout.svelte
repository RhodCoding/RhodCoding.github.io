<script>
    import "../app.css";
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet"> 
</svelte:head>

<main> <!--Navigation-->
    <nav>
        <h1>Portfolio</h1>
      <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/projects">Projects</a></li>
        <li><a href="/contact">Contact</a></li>
      </ul>
        <a href="https://github.com/RhodCoding" class="git">Github</a>
    </nav>
<slot></slot>
</main>