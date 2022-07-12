<script>
    import Title from "./Title.svelte"
</script>

<div class="about">
    <Title title="About Me"/>
    <p>I'm a 16 year old developer primarily making servers on Minecraft. I enjoy experimenting with new ideas or systems that push the boundaries of what Minecraft can do. In addition to that, I also enjoy making websites, discord bots, and other projects!</p>
</div>

<style>

    .about {
        border-bottom: 1px solid rgba(255, 255, 255, .2);
        text-align: center;
        background-color: #181818;
        padding: 5vh;
    }

    .about p {
        width: 40vw;
        margin: auto;
        padding-bottom: 5vh;
        font-size: 1.5rem;
    }

    @media (max-width: 768px) {
        .about p {
            width: 80vw;
        }
    }

</style>