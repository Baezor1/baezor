<script>
    import NavBar from "../components/NavBar.svelte"
    import Footer from "../components/Footer.svelte"
</script>

<svelte:head>
    <title>Baezor - TOS</title>
    <meta name="description" content="Terms of service for commissions.">
    <meta name="keywords" content="Baezor, Minecraft, Developer">
    <meta name="author" content="Baezor">
</svelte:head>

<div class="header">
    <div class="container">
        <h1>Terms of Service</h1>
    </div>
</div>

<p style="text-align: center; color: lightgray;">The terms of service for commissions. • Last edit on Augest 1, 2022.</p>
<div class="content">
    <h1>(1) General Terms</h1>
    <ol>
        <li>Do not ever redistribute scripts/files that were commissioned without permission. In order to get this permission, you must pay extra or work out a deal with the author.</li>
        <li>You will only receive your files after you have paid in full.</li>
        <li>Basic support and bug fixing will be available for the first two weeks.</li>
        <li>Advanced support and extra items will cost extra. Some examples of what is classfied as advanced/extra is listed below.</li>
        <ul>
            <li>Configuration and integration beyond what was promised.</li>
            <li>Adding extra pages/features after agreeing on features.</li>
            <li>Setting up databases or other services.</li>
        </ul>
        <li>For all projects that require databases, you must set up and maintain your own database.</li>
        <li>Parts of the scripts/files you receive may be reused in future projects.</li>
        <li>All commissions will be created on my own servers unless payment is 100% up front.</li>
    </ol>
    <h1>(2) Refund Terms</h1>
    <p>Refunds will not be granted unless any of the following events happen.</p>
    <ol>
        <li>Files are broken beyond repair.</li>
        <li>Failed to deliver commissioned files/scripts.</li>
    </ol>
    <h1>(3) Payment Terms</h1>
    <ol>
        <li>All payment will be through PayPal.</li>
        <li>You must pay in full before receiving your files/scripts.</li>
        <li>Offers for a percentage of ownership in your project will be rejected.</li>
        <li>Before starting your project, you must pay 50% up front.</li>
        <li>Requesting features outside of the original agreement will result in an extra charge.</li>
    </ol>
    <h1>(4) Skript Terms</h1>
    <ol>
        <li>Credit must remain in the script.</li>
        <ul>
            <li>You must keep the header credit.</li>
            <li>You must keep command credit if your command contains it.</li>
        </ul>
    </ol>
    <h1> (5) Website Terms</h1>
    <ol>
        <li>You must keep credit in the footer.</li>
        <li>All websites are created with SvelteKit, Github, and Vercel. Support will not be provided if you use an alternative host.</li>
    </ol>
</div>

<Footer />
<NavBar />

<style>
    .header {
        width: 100vw;
        text-align: center;
        padding-top: 10vh;
        padding-bottom: 10vh;
        border-bottom: 1px solid rgba(255, 255, 255, .2);
        margin-bottom: 0;
    }

    .container {
        width: 40vw;
        margin: auto;
        padding-top: 0;
    }

    .container h1 {
        font-size: 5rem;
        margin-bottom: 0;
        background: rgb(63,139,219);
        background: linear-gradient(128deg, rgba(63,139,219,1) 0%, rgba(177,34,71,1) 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
    }

    .content {
        width: 60vw;
        margin: auto;
    }

    .content p {
        font-size: 1.2rem;
        color: lightgray;
    }

    .content li {
        font-size: 1.2rem;
        color: lightgray;
        padding-bottom: 1vh;
    }

    @media (max-width: 768px) {

        .container h1 {
            font-size: 4rem;
        }

        .container {
            width: 80vw;
        }

        .content {
            width: 80vw;
        }
    }

</style>