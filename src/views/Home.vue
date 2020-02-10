<template>
  <div class="home">
    <b-alert show>
      <b-icon icon="info-fill" scale="2" variant="info" class="mx-2"></b-icon>
      Site under construction!
      <b-icon icon="tools"></b-icon>
    </b-alert>
    <b-img
      :src="require('../assets/steve.png')"
      fluid
      alt="Esteban image profile"
      rounded="circle"
      width="300" height="300"
    ></b-img>
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
  }
};
</script>
