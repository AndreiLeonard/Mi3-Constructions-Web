<template>
  <main>
    <div class="navbar">
      <NuxtLink class="NuxtLink" to="/"><p>Accueil</p></NuxtLink>
      <NuxtLink class="NuxtLink" to="/contact"><p>Contact</p></NuxtLink>
    </div>
    <div class="contact">
      <h1 class="contact-item">Addresse Mail du Gérant : adrian@mi3-constructions.com</h1>
      <br>
      <br>
      <h1 class="contact-item">Addresse Mail du Développeur : mi3.andreileonard@gmail.com</h1>
      <br>
      <br>
      <h1 class="contact-item">Numéro de Téléphone du Gérant : +33 06 64 67 63 53</h1>
    </div>
  </main>
</template>

<script>

  import * as pages from '/Sites/Mi3-Constructions-Web/pages/header.vue';

  export default {

  }

</script>

<style>
  * {
    font-family: Roboto, sans-serif;
  }
</style>