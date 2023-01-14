<script>
    import Navbar from "$lib/components/Navbar.svelte";
</script>

<style global>
    @import '$lib/styles/global.css';
</style>

<header>
    <Navbar />
</header>

<main>
    <slot></slot>
</main>

