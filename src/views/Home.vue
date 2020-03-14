<template>
  <div class="home">
    <b-img
      :src="require('../assets/steve.png')"
      fluid
      alt="Esteban image profile"
      rounded="circle"
      width="300"
      height="300"
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
