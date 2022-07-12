<script>
    import NavBar from "../components/NavBar.svelte"
    import Footer from "../components/Footer.svelte"
    import Skills from "../components/Skills.svelte"
    import About from "../components/About.svelte"
</script>

<div class="landing">
    <div class="container">
        <h1>Hello! I'm Baezor!</h1>
        <p>A developer working on a bunch of fun projects!</p>
    </div>
</div>
<About />
<Skills />
<Footer />
<NavBar />

<style>
    .landing {
        width: 100vw;
        text-align: center;
        padding-top: 10vh;
        padding-bottom: 10vh;
        background: rgb(18,18,18);
        background: linear-gradient(128deg, rgba(18,18,18,1) 0%, rgba(22,42,63,1) 28%, rgba(177,34,71,1) 100%);
        border-bottom: 1px solid rgba(255, 255, 255, .2);
        margin-bottom: 0;
    }

    .container {
        width: 40vw;
        margin: auto;
        padding-top: 0;
    }

    .container h1 {
        font-size: 7rem;
        margin-bottom: 0;
    }
    .container p {
        font-size: 2rem;
        color: lightgray;
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