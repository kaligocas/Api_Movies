<template>
    
        <Navbar/>
        <PopularMovies/>
        
    
</template>

<script>
    import Navbar from "./header/Navbar.vue";
    import PopularMovies from "./Popular-Movies.vue";


    export default{
        components: {
            Navbar,
            PopularMovies,
            
        },
            
    };
</script>

<style>

</style>