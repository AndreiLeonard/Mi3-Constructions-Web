<script>

  import * as pages from '/Sites/Mi3-Constructions-Web/pages/header.vue';

  export default {

  }

</script>

<template>
  <main>
    <title>Mi3-Constructions | Contact</title>
    <div class="navbar">
      <NuxtLink class="NuxtLink" to="/"><p>Accueil</p></NuxtLink>
      <NuxtLink class="NuxtLink" to="/contact"><p>Contact</p></NuxtLink>
      <NuxtLink class="NuxtLink" to="/galeries_photos"><p>Galeries Photos</p></NuxtLink>
    </div>
    <div class="photos">
        <div class="photo-item">
            <img class="photo-photo-item" src="../img/Mi3-Constructions_Logo.png" alt="Logo">
            <h1 class="photo-text-item">Notre Logo</h1>
        </div>
    </div>
  </main>
</template>

<style>
  * {
    font-family: Roboto, sans-serif;
  }
</style>