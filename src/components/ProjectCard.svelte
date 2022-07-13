<script>
    export let title
    export let desc
    export let tag
    export let link

    if (!tag) {
        tag = "Other"
    }
</script>

<div class="card">
    <a href={link} on:click={() => {window.location.href = link}}>
        <h1>{title}</h1>
        <p>{desc}</p>
        <div class="tag {tag}">
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

    .Website {
        background-color: #FBAB7E;
        background-image: linear-gradient(62deg, #FBAB7E 0%, #F7CE68 100%);
    }
    .Other {
        background-color: #FF9A8B;
        background-image: linear-gradient(90deg, #FF9A8B 0%, #FF6A88 55%, #FF99AC 100%);
    }

    .Skript {
        background-color: #08AEEA;
        background-image: linear-gradient(0deg, #08AEEA 0%, #2AF598 100%);

    }

    .Experiment {
        background-color: #FEE140;
        background-image: linear-gradient(90deg, #FEE140 0%, #FA709A 100%);

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