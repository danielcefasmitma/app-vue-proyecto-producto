<script setup>
import { RouterLink, RouterView } from 'vue-router';


</script>

<template>
  <RouterLink to="/">INICIO</RouterLink>
  <RouterLink to="/producto">PRODUCTOS</RouterLink>
  <RouterLink to="/login">INGRESAR</RouterLink>
  
  <RouterView/>
</template>
