<script>
    import Card from "./SkillCard.svelte"
    import Title from "./Title.svelte"
</script>

<Title title="Languages and Skills"/>
<div class="skills-container">
    <Card
        title="Skript"
        desc="Skript is a language used to create Minecraft servers. I've been using Skript for over 3 years and it got me into programming."
        img="https://avatars.githubusercontent.com/u/39464898?s=200&v=4"
        link="https://github.com/SkriptLang"
    />
    <Card
        title="Javascript"
        desc="I've used Javascript to create discord bots, websites, apis, and more!"
        img="https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg"
        link="https://www.javascript.com/"
    />
    <Card
        title="Python"
        desc="I use python for small projects and for basic automation tasks!"
        img="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg"
        link="https://www.python.org/"
    />
    <Card
        title="Svelte"
        desc="I primarily use Svelte and SvelteKit to create websites. This site is actually using SvelteKit!"
        img="https://upload.wikimedia.org/wikipedia/commons/1/1b/Svelte_Logo.svg"
        link="https://svelte.dev/"
    />
    <Card
        title="MongoDB"
        desc="I use MongoDB on almost all of my projects. Mongo is my go-to storage solution right now."
        img="https://www.vectorlogo.zone/logos/mongodb/mongodb-icon.svg"
        link="https://www.mongodb.com/"
    />
    <Card
        title="Redis"
        desc="I use redis a lot for server communication. It's amazing for a lot of things but I primarily use it for that."
        img="https://www.vectorlogo.zone/logos/redis/redis-icon.svg"
        link="https://redis.io/"
    />
</div>

<style>
    .skills-container {
        width: 100vw;
        margin: auto;
        padding-bottom: 5vh;
        display: flex;
        justify-content: center;
        align-items: left;
        align-content: center;
        flex-flow: row wrap;
        border-bottom: 1px solid rgba(255, 255, 255, .2)
    }

</style>