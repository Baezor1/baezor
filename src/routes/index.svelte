<script>
    import NavBar from "../components/NavBar.svelte"
    import Footer from "../components/Footer.svelte"
    import Skills from "../components/Skills.svelte"
    import About from "../components/About.svelte"
    import Contact from "../components/Contact.svelte"
</script>

<svelte:head>
    <title>Baezor</title>
    <meta name="description" content="A Minecraft server dedicated to building awesome games.">
    <meta name="keywords" content="Baezor, Minecraft, Developer">
    <meta property="og:image" content="https://cdn.discordapp.com/attachments/994279796588687421/1001913410507767918/favicon_baezor.png" />
</svelte:head>

<div class="landing">
    <div class="container">
        <h1>Hello!</h1>
        <h1>I'm Baezor!</h1>
        <p>A developer working on a bunch of fun projects!</p>
    </div>
</div>
<About />
<Skills />
<Contact />
<Footer />
<NavBar />

<style>
    .landing {
        width: 100vw;
        text-align: center;
        padding-top: 20vh;
        padding-bottom: 20vh;
        border-bottom: 1px solid rgba(255, 255, 255, .2);
        margin-bottom: 0;
    }

    .container {
        width: 80vw;
        margin: auto;
        padding-top: 0;
    }

    .container h1 {
        font-size: 7rem;
        margin: 0;
        background: rgb(63,139,219);
        background: linear-gradient(128deg, rgba(63,139,219,1) 0%, rgba(177,34,71,1) 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
    }
    .container p {
        font-size: 2rem;
        color: lightgray;
        margin: 0;
        margin-top: 2vh;
    }

    @media (max-width: 768px) {

        .container h1 {
            font-size: 4rem;
        }
        .container p {
            font-size: 1.5rem;
        }

        .container {
            width: 80vw;
        }
    }

</style>