<script>
    export let title
</script>

<h1 class="title">{title}</h1>

<style>
    .title {
        text-align: center;
        font-size: 4rem;
        transition: all 0.5s;
        margin-top: 0;
        padding-top: 4vh;
        margin-bottom: 0;
        padding-bottom: 4vh;
    }

    .title:hover {
        transform: scale(1.05);
        transition: all 0.5s;
    }

</style>