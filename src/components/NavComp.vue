<template>
  <div class="navegacao mb-5">
    <!-- Menu navegação -->
    <nav class="navbar bg-body-tertiary fixed-top">
        <div class="container-fluid">
            <router-link to="/inicio"><img alt="galeria digital logo" src="../assets/galeria_digital_logo.png"></router-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
                <div class="offcanvas-header">
                    <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Menu</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                </div>
                <div class="offcanvas-body">
                    <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                        <li class="nav-item p-2">
                            <router-link to="/inicio">Inicio</router-link>
                        </li>
                        <li class="nav-item p-2">
                            <router-link to="/catalogo">Catálogo</router-link>
                        </li>
                        <li class="nav-item p-2">
                            <router-link to="/sobre">Sobre</router-link>
                        </li>
                    </ul>
                    <form class="d-flex mt-3" role="search">
                        <input class="form-control me-2" type="search" placeholder="Buscar" aria-label="Search">
                        <button class="btn btn-outline-secondary" type="submit">Buscar</button>
                    </form>
                </div>
            </div>
        </div>
    </nav>
  </div>
</template>
<script>
export default {
  name: 'NavComp',
}
</script>
<!-- "scoped" CSS apenas para este compomente -->
<style scoped>
.navegacao{
    margin: 5px;
}
img{
   width: 50px;
}
a{
    color: black;
    text-decoration: none;
}
</style>