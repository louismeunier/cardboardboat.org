<script>
    import Section from "./Section.svelte";
    import Title from "./Title.svelte";
</script>

<style>
    img {
        max-width:100%;
        max-height:100%;
        height: auto;
    }

    .main {
        display: grid;
        grid-template-columns: 1fr 1fr;
    }

    p {
        font-size: 2em;
    }
</style>

<Section>
    <div class="main">
        <div>
            <Title
                title="The Idea"
                quote="The difficulty lies not in the new ideas, but in escaping the old ones."
                credit="John Maynard Kaynes"
            />
            <p>We set out, not to create a boat, but to create an experience.</p>
        </div>
        <img  src="images/patrickdramaticgray.png" alt="dramatic partick"/>
    </div>
</Section>