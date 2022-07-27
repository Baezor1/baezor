<script>

    export let logo

    if (!logo) {
        logo = "logo_white.svg"
    }

    function move() {
        window.location.href = "/"
    }
</script>

<div>
    <nav class="nav">
        <img on:click={move} src={logo} alt="">
        <div class="navitems">
            <a href="/" on:click={() => {
                window.location.href = "/"
            }}>Home</a>
            <a href="/projects" on:click={() => {
                window.location.href = "/projects"
            }}>Projects</a>
        </div>
    </nav>

</div>

<style>

    .nav {
        color: white;
        display: flex;
        align-items: center;
        justify-content: space-between;
        height: 7vh;
        width: 100vw;
        position: fixed;
        top: 0;
        background-color: rgba(255, 255, 255, 0);
        -webkit-backdrop-filter: blur(5px);
        backdrop-filter: blur(5px);
        border-bottom: 1px solid rgba(255, 255, 255, .2);

    }

    .navitems {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .nav img {
        height: 4vh;
        margin: 5vw;
        transition: all 0.5s;
    }

    .nav img:hover {
        transform: scale(1.1);
        transition: all 0.5s;
    }

    .nav a {
        color: white;
        text-decoration: none;
        margin: 5vw;
        transition: all 0.5s;
        font-weight: 600;
        font-size: 20px;
    }

    .nav a:hover {
        transform: scale(1.1);
        transition: all 0.5s;
    }

    @media (max-width: 768px) {

        .nav a {
            color: white;
            text-decoration: none;
            margin: 3vw;
            font-size: 15px;
        }

        .nav img {
            height: 5vh;
        }
	}

</style>