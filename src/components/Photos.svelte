<script>
import Section from "./Section.svelte";
import Title from "./Title.svelte";
import Carousel from "svelte-carousel";
</script>

<style>
    img {
        max-width: 100%;
        max-height: 100%;
    }
    .container {
        margin-top: 1em;
        display: grid;
        grid-template-columns: 1fr 1fr;
        align-items: center;
        justify-items: center;
        justify-content: center;
        gap: 1em;
    }
</style>
<Section>
    <Title
        title="Memories"
        quote="A picture is worth a thousand words, but a memory is priceless"
        credit="Some guy on Pinterest"
    />
    <div class="container">
        <div>
            <img src="/images/dabox.jpeg" alt="dabox"/>
        </div>
        <div>
        <img src="/images/bottom.jpeg" alt="dabox"/>
        </div>
        <div>
        <img src="/images/back.jpeg" alt="dabox"/>
        </div>
        <div>
        <img src="/images/focus.jpeg" alt="dabox"/>
        </div>
        <div>
        <img src="/images/onland.jpeg" alt="dabox"/>
        </div>
        <div>
        <img src="/images/sidel.jpeg" alt="dabox"/>
        </div>
        <div>
        <img src="/images/elliptical.jpeg" alt="dabox"/>
        </div>
        <div>
        <img src="/images/patrickoutside.jpeg" alt="dabox"/>
        </div>
        <div>
        <img src="/images/maazinsert.jpeg" alt="dabox"/>
        </div>
    </div>
</Section>