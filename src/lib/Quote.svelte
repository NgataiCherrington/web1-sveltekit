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

</style>