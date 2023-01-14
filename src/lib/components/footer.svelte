<script>
    import SocialIcons from "./social-icons.svelte";

</script>
<style>
    @import "$lib/styles/footer.style.css";
</style>

<div id="footer-container">

    <div id="footer-img-container">
        <img id="footer-image" src="/logo.svg" alt="">
    </div>

    <div id="footer-text">
        O SEU <span id="footer-text-color">PROBLEMA</span> E<br>
         <span id="footer-text-color">NOSSO</span> PROBLEMA
    </div>

    <div id="footer-social-icons">
        <SocialIcons/>
    </div>

    
</div>