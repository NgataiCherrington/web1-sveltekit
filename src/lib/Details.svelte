<script>
  let { detail } = $props(); 
</script>

<section>
    <img src="${detail.picture}" alt="sprite">
    <p>{details.firstName}</p>
    <p>{details.lastName}</p>
</section>

<style>
    section {
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
</style>