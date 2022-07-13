<script>
    import NavBar from "../../components/NavBar.svelte"
    import Footer from "../../components/Footer.svelte"
    import Contact from "../../components/Contact.svelte"
    import Text from "../../components/article/Text.svelte"
    import Image from "../../components/article/Image.svelte"
</script>

<div class="header">
    <div class="container">
        <h1>Personal Site</h1>
        <p>Article Written by Baezor</p>
    </div>
</div>

<Text header="Hello World!" line1="Welcome to my site! I created this site as a way to show off my projects! I created this site using SvelteKit and plain old CSS. I'm very new to web development, and I think this has turned out great! There isn't that much to show here as you are already on the site. I'll still leave a few images below though."/>
<Image img="https://cdn.discordapp.com/attachments/994279796588687421/996906553158414386/Screen_Shot_2022-07-13_at_5.30.40_PM.png"/>
<Image img="https://cdn.discordapp.com/attachments/994279796588687421/996906679818014770/Screen_Shot_2022-07-13_at_5.31.03_PM.png"/>
<Image img="https://cdn.discordapp.com/attachments/994279796588687421/996906680250011678/Screen_Shot_2022-07-13_at_5.31.10_PM.png"/>

<Footer />
<NavBar logo="../../../logo_white.svg" />

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

    .container p {
        font-size: 1.5rem;
        color: lightgray;
        margin-bottom: 0;
    }

    .article {
        padding-bottom: 10vh;
        padding-top: 10vh;
        padding-left: 30vw;
        padding-right: 30vw;
        border-bottom: 1px solid rgba(255, 255, 255, .2);
        background-color: #181818;
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