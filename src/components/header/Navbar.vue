<template>
  <nav class="navbar navbar-expand-lg bg-dark border-bottom">
        <div class="container-fluid">
            <img src="../../assets/img/Logo.png" alt="Logo" class="p-3">
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item p-4">
                        <router-link to="/movies" class="items1">Movies</router-link>
                    </li>
                    <li class="nav-item p-4">
                        <router-link to="/actors" class="items1">Actors</router-link>
                    </li>
                    
                    <li class="nav-item p-4">
                        <router-link to="/profile" class="items1">Profile</router-link>
                    </li>
                </ul>
            <form class="d-flex" role="search">
                <input class="form-control me-2 rounded-pill " type="search" placeholder="Search..." aria-label="Search">
                <img src="../../assets/img/avatar.png" alt="" class="rounded-circle" width="50">
            </form>
            </div>
        </div>
        
    </nav>
    
</template>

<script>

</script>

<style scoped>
      
     .items1{
        font-family: "Manrope", sans-serif;
        text-decoration: none !important;
        color: rgb(255, 255, 255);
        font-size: 20px;

    
    }
    .items1:hover{
        color: rgb(48, 193, 70);
    }
   
</style>