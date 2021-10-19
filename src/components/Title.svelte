<script lang="ts">
    export let title:string;
    export let quote:string;
    export let credit:string;
</script>

<style>
    h2 {
        font-size: 3em;
        text-decoration: underline;
    }
    i {
        font-size: 1.5em;
    }

    .credit {
        font-size: 1em;
    }
</style>

<h2>{title}</h2>
<i>{quote}</i>
<span class="credit">~ {credit}</span>