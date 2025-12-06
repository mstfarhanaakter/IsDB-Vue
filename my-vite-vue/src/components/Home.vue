<script setup lang="ts">
import Dash from './Dash.vue';
import Trees from './Trees.vue';


</script>

<template>
   <Navbar></Navbar>
    <Dash></Dash>
    <Trees></Trees>
    <router-view/>
    <Footer></Footer>
</template>