<script>
    import NavBar from "../components/NavBar.svelte"
    import Footer from "../components/Footer.svelte"

    let copy = "Baezor#0001"

    function copyText() {
        navigator.clipboard.writeText("play.minematic.io");
        copy = "Copied to Clipboard!"
    }
    
</script>

<div class="header">
    <div class="container">
        <h1>Contact</h1>
    </div>
</div>
<div class="contact-container">
    <div class="contact">
        <p>Hello! If you want to get in touch, the best way is through discord. You can add me at <a href="" on:click={copyText}>{copy}</a>. You can also click my name to copy it! 🙂</p>
    </div>
</div>
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

    .contact-container {
        padding-top: 20vh;
        padding-bottom: 20vh;
        border-bottom: 1px solid rgba(255, 255, 255, .2);
    }

    .contact p {
        font-size: 2rem;
        text-align: center;
        margin: auto;
        max-width: 40vw;
    }

    .contact a {
        text-decoration: wavy;
    }

    .contact a:hover {
        background: rgb(63,139,219);
        background: linear-gradient(128deg, rgba(63,139,219,1) 0%, rgba(177,34,71,1) 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
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