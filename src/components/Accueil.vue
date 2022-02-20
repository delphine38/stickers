<template>
  <h1 class="text-center">
    Stickers et Flocages 69 Vous souhaite la Bienvenue !
  </h1>

  <h3 class="text-center">Voici quelques projets éffectuer</h3>

  <div class="container">
    <img src="../assets/a.jpg" />
    <img src="../assets/c.jpg" />
    <img src="../assets/e.jpg" />
    <img src="../assets/f.jpg" />
    <img src="../assets/h.jpg" />
    <img src="../assets/i.jpg" />
    <img src="../assets/j.jpg" />
    <img src="../assets/k.jpg" />
  </div>

  <h3 class="text-center">
    Ceci est un échantillon, ensemble visualisons vos besoins
  </h3>
</template>


<!--script-->
<script>
export default {
  name: "Accueil",
};
</script>

<!--css-->
<style>
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: flex-start;
}
.container img {
  background-color: red;
  width: 200px;
}
</style>

