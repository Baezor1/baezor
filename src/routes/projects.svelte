<script>
    import NavBar from "../components/NavBar.svelte"
    import Footer from "../components/Footer.svelte"
    import Projects from "../components/Projects.svelte"
    import About from "../components/About.svelte"
</script>

<svelte:head>
    <title>Baezor - Projects</title>
    <meta name="description" content="A list of projects I have worked on.">
    <meta name="keywords" content="Baezor, Minecraft, Developer">
    <meta property="og:image" content="https://cdn.discordapp.com/attachments/994279796588687421/1001913410507767918/favicon_baezor.png" />
</svelte:head>

<div class="header">
    <div class="container">
        <h1>Projects</h1>
    </div>
</div>
<Projects />
<Footer />
<NavBar />

<style>
    .header {
        width: 100vw;
        text-align: center;
        padding-top: 10vh;
        padding-bottom: 10vh;
        border-bottom: 1px solid rgba(255, 255, 255, .2);
        margin-bottom: 0;
    }

    .container {
        width: 40vw;
        margin: auto;
        padding-top: 0;
    }

    .container h1 {
        font-size: 5rem;
        margin-bottom: 0;
        background: rgb(63,139,219);
        background: linear-gradient(128deg, rgba(63,139,219,1) 0%, rgba(177,34,71,1) 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
    }

    @media (max-width: 768px) {

        .container h1 {
            font-size: 4rem;
        }

        .container {
            width: 80vw;
        }
    }

</style>