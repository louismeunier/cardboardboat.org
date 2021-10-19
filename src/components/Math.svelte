<script>
    import Section from "./Section.svelte";
    import Title from "./Title.svelte";
</script>

<style>
    img {
        max-height: 100%;
        max-width: 100%;
        height: auto
    }

    .header {
        display: grid;
        grid-template-columns: 1fr 1fr;
    }

</style>
<Section>
    <div class="header">
        <img src="images/maazedit.png" alt="maaz"/>
        <div>
            <Title
                title="The Math"
                quote="Pure mathematics is, in its way, the poetry of logical ideas."
                credit="Albert Einstein"
            />
        </div>
    </div>
</Section>