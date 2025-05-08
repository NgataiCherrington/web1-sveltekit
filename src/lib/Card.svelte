<script>
   import Picture from "./Picture.svelte";
   import Details from "./Details.svelte";
</script>

<div>
    <Picture />
    <Details />
</div>

<style>
    div {
        border: 1px solid black;
        max-width: 250px;
        background-color: aqua;
        box-shadow: 2px 2px #333;
        margin: 0 1em 1em 0;
        padding: 0.8em;
    }

</style>