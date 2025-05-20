<script>
    import Footer from "$lib/Footer.svelte";
    import Header from "$lib/Header.svelte";
    
    let  { children } = $props();
</script>

<!-- Include the main heading and navigation -->
<Header />

<!-- This is where the page content will go-->
{@render children()}

<!-- Include footer -->
<Footer />

<style>

</style>