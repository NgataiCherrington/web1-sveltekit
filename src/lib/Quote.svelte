<script>
    let { quote } = $props();
</script>

<div>
    <blockquote>
        <p>{quote.quoteText}</p>
    </blockquote>
    <p>-{quote.author}</p>
</div>

<style>
    div {
        border: 1px dashed grey;
        border-radius: 10px;
        background-color: burlywood;
        margin: 1em;
        padding: 1em;
    }

    blockquote {
        border-left: 0.5em solid tomato;
    }

    
</style>