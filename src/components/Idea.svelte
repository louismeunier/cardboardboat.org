<script>
    import CardboardBox from "./CardboardBox.svelte";
import DuctTape from "./DuctTape.svelte";
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

    .beauty {
        width: 100%;
        display: grid;
        grid-template-columns: 1fr 1fr;
    }

    :global(.beauty svg) {
        max-width:100%;
        max-height:100%;
        height: auto;
    }

    :global(.ductape) {
        animation: infinite 5s 0s approachRight;
    }

    :global(.cardboard) {
        animation: infinite 5s 0s approachLeft;
    }
    @keyframes approachLeft {
        0% {transform: translateX(-20vw);}
        50% {transform: translateX(20vw);}
        100% {transform: translateX(-20vw);}
    }

    @keyframes approachRight {
        0% {transform: translateX(20vw);}
        50% {transform: translateX(-20vw);}
        100% {transform: translateX(20vw);}
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
            <p>An experience of two, disjunct materials coming together in harmony.</p>
        </div>
        <img  src="images/patrickdramaticgray.png" alt="dramatic partick"/>
    </div>
    <div class="beauty">
        <CardboardBox/>
        <DuctTape/>
    </div>
</Section>