<script>
    import Navbar from '$lib/components/navbar.svelte'
</script>

<Navbar />
<main>
    <slot></slot>
</main>


<style>
    main {
        padding: 3em;
    }
</style>