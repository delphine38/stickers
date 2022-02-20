<template>
  <entete></entete>
  <accueil></accueil>
  <reseaux></reseaux>
</template>

<script>
import Entete from "./components/Entete.vue";
import Accueil from "./components/Accueil.vue";
import Reseaux from "./components/Reseaux.vue";
export default {
  name: "App",
  components: {
    Entete,
    Accueil,
    Reseaux,
  },
};
</script>

<style>
</style>