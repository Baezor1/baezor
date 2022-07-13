<script>
    import Title from "./Title.svelte"

    let copy = "Baezor#0001"

    function copyText() {
        navigator.clipboard.writeText("Baezor#0001");
        copy = "Copied to Clipboard!"
    }
</script>

<div class="contact">
    <Title title="Contact"/>
    <p>Hello! If you want to get in touch, the best way is through discord. You can add me at <a href="" on:click|preventDefault={copyText}>{copy}</a>. You can also click my name to copy it! 🙂</p>
    <br>
    <p>In addition to my personal discord, you can also join my discord server <a href="https://discord.gg/4Ev7NbuTHY">here</a>! </p>
</div>

<style>

    .contact {
        border-bottom: 1px solid rgba(255, 255, 255, .2);
        text-align: center;
        background-color: #181818;
        padding: 5vh;
    }

    .contact p {
        width: 40vw;
        margin: auto;
        padding-bottom: 5vh;
        font-size: 1.5rem;
    }

    .contact a {
        color: rgba(63,139,219,1);
    }

    @media (max-width: 768px) {
        .contact p {
            width: 80vw;
        }
    }

</style>