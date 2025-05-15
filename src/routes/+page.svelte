<script>
    import Header from "$lib/Header.svelte"
    import Footer from "$lib/Footer.svelte";
    import Card from "$lib/Card.svelte";
    import Quote from "$lib/Quote.svelte";
  import Navigation from "$lib/Navigation.svelte";

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
        },
        {
            quoteText: "Love is composed of a single soul inhabiting two bodies",
            author: "Heraclitus"
        }
    ];


    let cards = [
        {
            title: "My Card",
            user: {
                userName: "@ngaaats",
                img: "https://i.gifer.com/origin/2f/2f548a4cff82755977ae34fe08e4ac50_w200.gif"
            },
            info: "Info goes here"
        }
    ]

</script>


<Header />
<Navigation />
{#each quotes as quote}
    <Quote {quote}/>
{/each}

<main class="card-grid">
   
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
