<template>
  <div>
    <b-navbar id="navbar-mobile">
      <b-navbar-brand href="#">
        <b-img
          :src="require('../assets/steve.png')"
          fluid
          alt="Esteban image profile"
          rounded="circle"
          width="75"
          height="75"
        ></b-img>
      </b-navbar-brand>
      <div id="menu">
        <router-link to="/">EN</router-link> | 
        <router-link to="/es">ES</router-link>
      </div>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
#menu {
  padding: 30px;
  align-content: center;
}

#menu a {
  font-weight: bold;
  color: #2c3e50;
}

#menu a.router-link-exact-active {
  color: #42b983;
}
#navbar-mobile{
    position: fixed;
    background-color: rgba(255,255,255, 0.95);
    width: 100%;
}

/* Small screens */
@media only screen and (min-width: 600px) {
  #navbar-mobile {
    display: none;
  }
}
</style>
