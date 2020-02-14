<template>
  <div>
    <ul>
      <li>
        <a
          href="https://ar.linkedin.com/in/estebanmellado"
          target="_blank"
          rel="noopener"
        >
          <b-img
            :src="require('../assets/linkedinLogo.png')"
            fluid
            alt="Linkedin Logo"
            width="70"
            height="70"
          ></b-img>
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/m_esteban90"
          target="_blank"
          rel="noopener"
        >
          <b-img
            :src="require('../assets/twitterLogo.png')"
            fluid
            alt="Twitter Logo"
            width="75"
            height="75"
          ></b-img>
        </a>
      </li>
      <li>
        <a
          href="https://github.com/EstebanMellado"
          target="_blank"
          rel="noopener"
        >
          <b-img
            :src="require('../assets/githubLogo.png')"
            fluid
            alt="Github Logo"
            width="70"
            height="70"
          ></b-img>
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "SocialNetworks"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>
