<script>
    export let img
</script>

<div class="img-container">
    <img src={img} alt="">
</div>

<style>
    .img-container {
        width: 100vw;
    }

    .img-container img {
        max-width: 80vw;
        margin-left: 10vw;
        margin-top: 5vh;
        margin-bottom: 5vh;
    }
</style>