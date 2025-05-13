<script>
    import Header from "$lib/Header.svelte"
    import Footer from "$lib/Footer.svelte";
    import Card from "$lib/Card.svelte";
    import Quote from "$lib/Quote.svelte";
</script>

<Header />
<Quote />

<main class="card-grid">
    <Card />
    <Card />
    <Card />
</main>

<Footer />

<style>
    main {
        display: flex;
    }

    .card-grid {
        display: grid;
        grid-template-columns: auto auto auto;
    }
</style>
