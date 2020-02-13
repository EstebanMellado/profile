<template>
  <div class="home-es">
    <b-alert show>
      <b-icon icon="info-fill" scale="2" variant="info" class="mx-2"></b-icon>Sitio en construcción!
      <b-icon icon="tools" scale="1.5" class="mx-2"></b-icon>
    </b-alert>
    <b-img
      :src="require('../assets/steve.png')"
      fluid
      alt="Esteban foto de perfil"
      rounded="circle"
      width="300"
      height="300"
    ></b-img>
    <h1>Hola, soy Esteban</h1>
    <p>Nacido en el 90 y codeando desde 2017. Siempre trabajé en el mundo IT. Motivado por nuevo desafíos, y siempre con ganas de aprender nuevas tecnologías.</p>
    <p>Cuando no estoy codeando, estoy haciendo algun deporte o juntándome con amigos o yendo a meetups para hacer networking y conocer a otros desarrolladores.</p>
    <p>En 2018 me convertí en orador en algunos eventos nacionales e internacionales de tecnología, esto despertó algo nuevo en mí y me dió maravillosas experiencias arriba del escenario compartiendo lo que sé.</p>

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
  