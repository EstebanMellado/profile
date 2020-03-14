<template>
  <div class="home-es">
    <b-img
      :src="require('../assets/steve.png')"
      fluid
      alt="Esteban foto de perfil"
      rounded="circle"
      width="300"
      height="300"
    ></b-img>
    <h1>Hola, soy Esteban</h1>
    <div class="container">
      <div class="row">
        <div class="column">
          <p>
            Nacido en el 90 y codeando desde 2017. Siempre trabajé en el mundo
            IT. Motivado por nuevos desafíos, y siempre con ganas de aprender
            nuevas tecnologías.
          </p>
        </div>
        <div class="column">
          <p>
            Cuando no estoy codeando, estoy haciendo algún deporte o juntándome
            con amigos o yendo a meetups para hacer networking y conocer a otros
            desarrolladores.
          </p>
        </div>
        <div class="column">
          <p>
            En 2019 me convertí en orador en algunos eventos nacionales e
            internacionales de tecnología, esto despertó algo nuevo en mí y me
            dió maravillosas experiencias arriba del escenario compartiendo lo
            que sé.
          </p>
        </div>
      </div>
    </div>

    <h3>Algunos de mis conocimientos</h3>
    <Skills />

    <h3>Links Recomendados</h3>
    <SocialNetworks />
  </div>
</template>

<script>
import Skills from "@/components/Skills.vue";
import SocialNetworks from "@/components/SocialNetworks.vue";

export default {
  name: "About",
  components: {
    Skills,
    SocialNetworks
  }
};
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}

* {
  box-sizing: border-box;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
