<script>
    export let header
    export let line1
    export let line2
    export let line3
    export let line4
</script>

<div class="text">
    {#if header}
    <h1>{header}</h1>
    {/if}
    {#if line1}
    <br>
    <p>{line1}</p>
    {/if}
    {#if line2}
    <br>
    <p>{line2}</p>
    {/if}
    {#if line3}
    <br>
    <p>{line3}</p>
    {/if}
    {#if line4}
    <br>
    <p>{line4}</p>
    {/if}
</div>

<style>
    .text {
        padding-bottom: 5vh;
        padding-top: 5vh;
        padding-left: 25vw;
        padding-right: 25vw;
        border-bottom: 1px solid rgba(255, 255, 255, .2);
        background-color: #181818;
    }

    .text p {
        margin-top: 0;
        padding-top: 0;
        color: lightgray;
        font-size: 1.5rem;
    }

    .text h1 {
        margin-top: 0;
        padding-top: 0;
        font-size: 3rem;
    }

    @media (max-width: 768px) {
        .text {
            padding-left: 10vw;
            padding-right: 10vw;
        }
    }
</style>