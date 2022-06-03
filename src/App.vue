<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <header>
    <h1>Trippy</h1>
      <nav>
        <RouterLink to="/">Accueil |</RouterLink>
        <RouterLink to="/restaurants"> Restaurants |</RouterLink>
        <RouterLink to="/hotels"> Hotels |</RouterLink>
        <RouterLink to="/about"> A propos </RouterLink>
      </nav>
  </header>
  <RouterView />
</template>

<style>
@import '@/assets/styles/base.css';
</style>
