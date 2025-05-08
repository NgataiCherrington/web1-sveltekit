<script>
    import Header from "$lib/Header.svelte"
    import Footer from "$lib/Footer.svelte";
    import Card from "$lib/Card.svelte";
</script>

<Header />

<main>
    <Card />
    <Card />
</main>

<Footer />

<style>
    main {
        display: flex;
    }
</style>
