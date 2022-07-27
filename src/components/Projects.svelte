<script>
    import Card from "./ProjectCard.svelte"
    import Title from "./Title.svelte"
</script>

<div class="projects-container">
    <!-- Yes I'm Hard Coding This Deal with it -->
    <Card
        title="Minematic"
        desc="Minematic is a Minecraft server I'm working on where you can create your own games!"
        year="2022"
        discord="https://discord.gg/Gyy26QfpNa"
        link="https://minematic.io/"
    />
    <Card
        title="Personal Site"
        desc="The website you are currently on! This site was created with SvelteKit!"
        year="2022"
        link="https://baezor.com/"
        github="https://github.com/Baezor1/baezor"
    />
    <Card
        title="Minematic Site"
        desc="The website for the Minematic network. This was created with SvelteKit."
        year="2022"
        link="https://minematic.io/"
    />
    <Card
        title="Factory"
        desc="This server was created as a commission for the Orefield network. You can build your own factory and grind your way to the top!"
        year="2022"
        discord="https://discord.com/invite/h2eEjk26Kz"
    />
    <Card
        title="Box Clear"
        desc="A script you can purchase on the Minehut marketplace!"
        year="2022"
        link="https://shop.minehut.com/products/box-clear"
    />
    <Card
        title="Minezone"
        desc="Minezone was a survival server with many custom features. This server has been closed for awhile now."
        year="2021"
    />
    <Card
        title="Skript Crates"
        desc="A script you can purchase on the Minehut marketplace!"
        year="2021"
        link="https://shop.minehut.com/products/skript-crates"
/>
</div>

<style>
    .projects-container {
        width: 100vw;
        margin: auto;
        padding-bottom: 5vh;
        display: flex;
        justify-content: center;
        align-items: left;
        align-content: center;
        flex-flow: column wrap;
        border-bottom: 1px solid rgba(255, 255, 255, .2);
        padding-top: 5vh;
    }

</style>