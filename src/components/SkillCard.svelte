<script>
    export let title
    export let desc
    export let img
    export let link
</script>

<div class="card">
    <a href={link} target="_blank">
        <img src={img} alt="">
        <h1>{title}</h1>
        <p>{desc}</p>
    </a>
</div>

<style>

    .card {
        width: 17vw;
        background-color: #181818;
        margin: 1vw;
        padding: 1vw;
        border-radius: 8px;
        text-align: center;
        transition: all 0.5s;
        overflow: hidden;
    }

    .card img {
        max-width: 10vw;
        height: 10vw;
    }

    .card:hover {
        transition: all 0.5s;
        transform: scale(1.05);
    }

    .card a {
        text-decoration: none;
        color: white;
    }

    @media (max-width: 768px) {
        .card {
            width: 80vw;
            margin: 3vh;
            padding: 3vh;
        }

        .card img {
            max-width: 20vw;
            max-height: 20vw;
        }
    }

</style>