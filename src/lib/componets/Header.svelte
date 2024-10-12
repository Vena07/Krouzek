<script>

</script>

<header>
    <nav>
        <a class = "Home" href="/">Home</a>
        <a class="About" href="/about">About</a>
        <a class="Svelte" href="/">Svelte</a>
    </nav>
</header>

<style>
    header{
        height: 60px;
        background-color: gray;
        display: flex;
        justify-content: flex-end;
        align-items: center;
        border-radius: 10px;
    }

    .Home, .About, .Svelte{
        margin-right: 15px;
        color: white;
        font-size: 25px;
        border: solid 3px  rgb(100, 99, 99);
        padding: 5px;
        background-color: rgb(100, 99, 99);
        text-decoration: none;
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        border-radius: 10px;
        transition: all 0.2s ease;


    }

    .Home:hover, .About:hover, .Svelte:hover{
        background-color: white;
        color: black;
    }

</style>