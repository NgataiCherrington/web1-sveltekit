<script>
   import Details from "./Details.svelte";

   let { detail } = $props(); 
   let user = detail.user;
</script>

<div>
    <Details {detail}/>
</div>

<style>
    div {
        border: 1px solid black;
        max-width: 250px;
        background-color: aqua;
        box-shadow: 2px 2px #333;
        margin: 0 1em 1em 0;
        padding: 0.8em;
        display: flex;
        flex-direction: column;
    }

</style>