<script>
    let title = "super cool";
    import Card from "$lib/components/Card.svelte";
</script>

<h1>Welcome to a {title} SvelteKit</h1>

<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
<p>Welcome to a website</p>
<img src = "https://www.nbcstore.com/cdn/shop/products/SHREK-SS-63-MF1_576x.jpg?v=1693905182" alt="Shrek">
<h2>Hello</h2>

<Card name = {"Olivia"}/>
<Card name = {"Fundamentals of web dev"}/>
<Card />

<style>
    h1{
        color: red;
        background-color: black;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-size: 2em;
    }

    h2{
        color: blueviolet;
        font-size: 1.5em;
        font-family: 'Courier New', Courier, monospace;
    }

    p{
        color: green;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
    }
    
    img{
        border: solid 15px greenyellow;
        border-radius: 3%;
    }
</style>

