<script setup>
import "../assets/inicio.css";
import { RouterLink, RouterView } from 'vue-router'


</script>

<template>
<header>
<nav>
        <RouterLink to="/articulos">Artículos</RouterLink>
        <RouterLink to="/about">Contacto</RouterLink>
</nav>
</header>

<RouterView />

</template>


