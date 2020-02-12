<template>
  <div class="home-es">
    <b-alert show>
      <b-icon icon="info-fill" scale="2" variant="info" class="mx-2"></b-icon>Sitio en construcción!
      <b-icon icon="tools" scale="1.5" class="mx-2"></b-icon>
    </b-alert>
    <b-img
      :src="require('../assets/steve.png')"
      fluid
      alt="Esteban foto perfil"
      rounded="circle"
      width="300"
      height="300"
    ></b-img>
    <h1>Hola, soy Esteban</h1>
    <p>Tarea: escribir un breve descrición de mí.</p>
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
</style>
  