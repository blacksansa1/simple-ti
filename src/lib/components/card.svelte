<script>
    export let src = ""
    export let title = ""
</script>

<style>
    @import "$lib/styles/card.style.css";
</style>

<div id="card-container">
    <img id="card-image" src={src} alt="">
    <div id="card-title">
        {title}
    </div>
</div>
