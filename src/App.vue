<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>
<template>
  <nav>
    <ul class="flex gap-6">
      <li><RouterLink class=" " to="/"> Accueil</RouterLink></li>
      <li> <RouterLink class=" " to="/Tendances"> Tendances</RouterLink></li>
      <li> <RouterLink class=" " to="/Glossaire"> Glossaire</RouterLink></li>
      <li> <RouterLink class=" " to="/Don">Faire un don</RouterLink></li>
      <li> <RouterLink class=" " to="/Inscrire">S’inscrire</RouterLink></li>
    </ul>
  </nav>

  <!-- Affiche les pages -->
  <Router-View/>
</template>

<script>
import { MenuIcon } from "@heroicons/vue/solid";

export default {
  name: "App",
  components: { MenuIcon },
};
</script>
