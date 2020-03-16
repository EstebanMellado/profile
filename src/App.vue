<template>
  <div id="app">
    <Navbar />
    <div id="nav">
      <router-link to="/">English</router-link>|
      <router-link to="/es">Español</router-link>
    </div>
    <router-view />
    <br />
    <Footer />
  </div>
</template>

<script>
import Footer from "@/components/Footer.vue";
import Navbar from "@/components/Navbar.vue";

export default {
  name: "App",
  components: {
    Footer,
    Navbar
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

/* Small screens */
@media only screen and (max-width: 600px) {
  #nav {
    display: none;
  }
}
</style>
