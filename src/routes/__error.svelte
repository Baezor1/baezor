<script context="module">
    /** @type {import('@sveltejs/kit').Load} */
    export function load({ error, status }) {
        return {
            props: {
                status: `${status}`,
            }
        };
    }
</script>

<script>
    export let status;

    function home() {
        window.location.href = "/"
    }

</script>

<svelte:head>
    <title>Error {status}</title>
</svelte:head>

<div class="background">
    <div class="fade">
        <div class="flex">
            <h1>{status}</h1>
            <p>An error occured while trying to get to this page!</p>
            <button on:click={home}>Back to Safety!</button>
        </div>
    </div>
</div>

<style>
    .background {
        background: rgb(18,18,18);
        background: linear-gradient(128deg, rgba(18,18,18,1) 0%, rgba(199,77,4,1) 33%, rgba(122,31,25,1) 100%);

        height: 100vh;
        width: 100vw;
        overflow: hidden;
    }

    .fade {
        background-color: rgba(18,18,18,0.3);
        height: 100vh;
        width: 100vw;
        display: flex;
        justify-content: left;
        align-items: center;
        align-content: center;
        padding-left: 1vw;
        padding-right: 1vw;
    }

    .flex {
        display: flex;
        justify-content: center;
        align-items: left;
        align-content: center;
        flex-flow: column wrap;
        text-align: left;
        width: 60vw;
        margin: 0;
        margin-bottom: 1vh;
    }

    .flex h1 {
        font-size: 7vh;
        margin: 0;
        margin-bottom: 1vh;
    }

    .flex p {
        font-size: 2vh;
        color: lightgray;
        margin: 0;
        margin-bottom: 2vh;
    }

    .flex button {
        margin-bottom: 1vh;
        opacity: 100%;
        width: 10vw;
    }

    @media (max-width: 768px) {

        .fade {
            justify-content: center;
        }

        .flex {
            text-align: center;
        }

        .flex button {
            width: 100%;
        }

        .content {
            width: 80vw;
        }

    }

</style>