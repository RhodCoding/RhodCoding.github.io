<script>
    import "../app.css";
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet"> 
</svelte:head>

<main> <!--Navigation-->
 <div class="top">
    <p>test</p>
 <nav>
    <a href="/">Home</a>
    <a href="/page-two">Page2</a>
    <a href="/">More</a>
    <a href="/">More</a>
 </nav>
    <a href="/">Login</a>
</div>
<slot></slot>
</main>