<script>
    import Header from "$lib/Header.svelte"
    import Footer from "$lib/Footer.svelte";
    import Card from "$lib/Card.svelte";
    import Quote from "$lib/Quote.svelte";

    let quotes = [
        {
            quoteText: "I think therefore, I am",
            author: "Rene Descartes"
        },
        {
            quoteText: "One think i know, that i know nothing. This is the source of my wisdom.",
            author: "Socrates"
        },
        {
            quoteText: "There is nothing permanent except change",
            author: "Heraclitus"
        }
    ];


</script>

<Header />
{#each quotes as quote}
    <Quote {quote}/>
{/each}

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
