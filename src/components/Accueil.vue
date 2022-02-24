<template>
  <h1 class="text-center my-5">
    Stickers et Flocages 69 Vous souhaite la Bienvenue !
  </h1>
  <h2 class="text-center my-5">
    Chez Stick flock 69, nous faisons sur mesure et personnalisé vos stickers et
    flocages. <br />
    Pour toutes commandes, envoyer un mail à : alice@protonmail.com
  </h2>

  <h3 class="text-center m-5">Quelques flocages :</h3>

  <div class="container">
    <article>
      <img src="../assets/sacboule.jpg" />
      <p>Sac de boule personnalisé</p>
    </article>

    <article>
      <img src="../assets/teeshirtpauline.jpg" />
      <img src="../assets/sacpauline.jpg" />
      <p class="text-center">Remerciements pour fin d'année scolaire</p>
    </article>

    <article>
      <img src="../assets/teeshirtmecsuper.jpg" />
      <p>Ce mec .....</p>
    </article>

    <article>
      <img src="../assets/jopizza.jpg" />
      <p>Jo Pizza</p>
    </article>

    <article>
      <img src="../assets/cacheplaque.jpg" />
      <p>Cache Plaque</p>
    </article>

    <article>
      <img src="../assets/fakewheels.jpg" />
      <p>Stick sur jantes</p>
    </article>
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

