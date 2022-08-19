<script>
    import Card from "./ProjectCard.svelte"
</script>

<div class="projects-container">
    <!-- Yes I'm Hard Coding This Deal with it -->
    <Card
        title="Icey's Website"
        desc="A website commissioned by Icey."
        year="2022"
        link="https://icey.gg/"
        img=""
    />
    <Card
        title="Quartz Website"
        desc="A website commissioned for Quartz Studios LTD."
        year="2022"
        link="https://qrtz.gg/"
        img=""
    />
    <Card
        title="NavaLabs Website"
        desc="A website commissioned for NavaLabs."
        year="2022"
        link="https://navalabs.net/"
        img="https://cdn.discordapp.com/attachments/994279796588687421/1003103456845906071/Screen_Shot_2022-07-30_at_7.54.46_PM.png"
    />
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
        img="https://cdn.discordapp.com/attachments/994279796588687421/1003103456493576283/Screen_Shot_2022-07-30_at_7.54.38_PM.png"
    />
    <Card
        title="Minematic Site"
        desc="The website for the Minematic network. This was created with SvelteKit."
        year="2022"
        link="https://minematic.io/"
        img="https://cdn.discordapp.com/attachments/994279796588687421/1003103457139494912/Screen_Shot_2022-07-30_at_7.54.56_PM.png"
    />
    <Card
        title="Factory"
        desc="This server was created as a commission for the Orefield network. You can build your own factory and grind your way to the top!"
        year="2022"
        discord="https://discord.com/invite/h2eEjk26Kz"
        img="https://cdn.discordapp.com/attachments/941319229825744946/980695743641837588/Screen_Shot_2022-05-29_at_11.53.58_PM.png"
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
        img="https://cdn.discordapp.com/attachments/880633574766805044/898681522368942080/SPOILER_Screen_Shot_2021-10-15_at_4.18.41_PM.png"
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