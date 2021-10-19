<style>
    .wrapper {
        width: 100%;
        display: grid;
        place-items: center;
    }

    .main {
        min-width: 50%;
        width: 75%;
        max-width: 100%;
        padding: 2em;
        display: grid;
        grid-auto-flow: row;
        justify-content: start;
        justify-items: left;

    }
</style>

<div class="wrapper">
    <div class="main">
        <slot/>
    </div>
</div>