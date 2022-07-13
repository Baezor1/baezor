<script>
    import Card from "./ProjectCard.svelte"
    import Title from "./Title.svelte"
</script>

<div class="projects-container">
    <!-- Yes I'm Hard Coding This Deal with it -->
    <Card
        title="Personal Site"
        desc="The website you are currently on! This site was created with SvelteKit!"
        link="/projects/personal-site"
        tag="Website"
    />
    <Card
        title="Minematic Site"
        desc="The website for the Minematic network. This was created with SvelteKit."
        link="/projects/minematic-site"
        tag="Website"
    />
    <Card
        title="Minematic"
        desc="Minematic is a Minecraft server I'm working on where you can create your own games!"
        link="/projects/minematic"
        tag="Minecraft"
    />
    <Card
        title="Factory"
        desc="This server was created as a commission for the Orefield network. You can build your own factory and grind your way to the top!"
        link="/projects/factory"
        tag="Minecraft"
    />
    <Card
        title="Minezone"
        desc="Minezone was a survival server with many custom features. This server has been closed for awhile now."
        link="/projects/minezone"
        tag="Minecraft"
    />
    <Card
        title="Skript Crates"
        desc="A script you can purchase on the Minehut marketplace!"
        link="/projects/skript-crates"
        tag="Skript"
    />
    <Card
    title="Box Clear"
    desc="A script you can purchase on the Minehut marketplace!"
    link="/projects/box-clear"
    tag="Skript"
    />
    <Card
        title="Cool Experiments"
        desc="A collection of experiments in the Skript language."
        link="/projects/skript-crates"
        tag="Experiment"
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
        flex-flow: row wrap;
        border-bottom: 1px solid rgba(255, 255, 255, .2);
        padding-top: 5vh;
    }

</style>