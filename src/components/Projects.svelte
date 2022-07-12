<script>
    import Card from "./ProjectCard.svelte"
    import Title from "./Title.svelte"
</script>

<div class="projects-container">
    <Card
        title="Skript"
        desc="Skript is a language used to create Minecraft servers. I've been using Skript for over 3 years and it got me into programming."
        img="https://avatars.githubusercontent.com/u/39464898?s=200&v=4"
        link="/projects/skript"
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