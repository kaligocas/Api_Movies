<template>
    <div class="container-fluid text-light">
        <h2 class="text-warning">Más Populares</h2>
        <MoviesItem/>
    </div>
</template>

<script>
    import MoviesItem from "./items/MovieItem.vue";
    export default {
        components: {
            MoviesItem,
        },
    }
</script>

<style scoped>
    h2{
        font-family: "League Spartan", sans-serif;
    }

</style>