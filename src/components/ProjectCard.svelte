<script>
    export let title
    export let desc
    export let tag
    export let link

    if (!tag) {
        tag = "Minecraft"
    }
</script>

<div class="card">
    <a href={link}>
        <h1>{title}</h1>
        <p>{desc}</p>
        <div class="tag">
            <p>{tag}</p>
        </div>
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

    .tag {
        background-color: #85FFBD;
        background-image: linear-gradient(45deg, #85FFBD 0%, #FFFB7D 100%);
        color: #121212;
        border-radius: 8px;
        width: 70%;
        margin: auto;
    }

    .tag p {
        padding: 5px;
        font-weight: 500;
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