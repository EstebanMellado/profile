<template>
  <div class="home">
    <div id="profileImage"
    class="fondo"
        v-bind:class="{ hideImage: isActive }">
      <b-img
        :src="require('../assets/steve.png')"
        fluid
        alt="Esteban image profile"
        rounded="circle"
        width="300"
        height="300"
      ></b-img>
    </div>
    <HelloWorld msg="Welcome to Esteban's profile" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  },
  data: function() {
    return {
      isActive: false,
      hideImage: 'image-mobile'
    };
  },
  mounted() {
    this.$nextTick(function() {
      window.addEventListener("scroll", function() {
        if (document.documentElement.scrollTop >= 100) {
          this.isActive = true;
          console.log("ocultar imagen, mostrar navbar");
          console.log(this.isActive);
        } else {
          this.isActive = false;
          console.log("mostrar imagen, ocultar navbar");
          console.log(this.isActive);
        }
      });
    });
  }
};
</script>

<style>
.image-mobile {
  /* display: none; */
  background-color: blue;
}
.fondo{
  background-color: blueviolet;
}
</style>
