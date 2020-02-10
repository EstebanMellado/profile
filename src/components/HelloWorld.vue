<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,
      <br />check out the
      <a
        href="https://cli.vuejs.org"
        target="_blank"
        rel="noopener"
      >vue-cli documentation</a>.
    </p>
    <h3>Some of my skills</h3>
    <ul>
      <li>
        <a href="https://dotnet.microsoft.com/" target="_blank" rel="noopener">
          <b-img
            :src="require('../assets/netCoreLogo.svg.png')"
            fluid
            alt="Net Core Logo"
            width="50"
            height="50"
          ></b-img>
        </a>
      </li>
      <li>
        <a href="https://nodejs.org/es/" target="_blank" rel="noopener">
          <b-img
            :src="require('../assets/nodeLogo.jpg')"
            fluid
            alt="Node.js Logo"
            width="70"
            height="70"
          ></b-img>
        </a>
      </li>
      <li>
        <a href="https://vuejs.org/" target="_blank" rel="noopener">
          <b-img
            :src="require('../assets/vueLogo.png')"
            fluid
            alt="Vue.js Logo"
            width="50"
            height="50"
          ></b-img>
        </a>
      </li>
      <li>
        <a href="https://angular.io/" target="_blank" rel="noopener">
          <b-img
            :src="require('../assets/angularLogo.svg.png')"
            fluid
            alt="Angular Logo"
            width="70"
            height="70"
          ></b-img>
        </a>
      </li>
      <li>
        <a href="https://www.mongodb.com/" target="_blank" rel="noopener">
          <b-img
            :src="require('../assets/mongodbLogo.png')"
            fluid
            alt="Mongodb Logo"
            width="70"
            height="70"
          ></b-img>
        </a>
      </li>
      <li>
        <a href="https://en.wikipedia.org/wiki/SQL" target="_blank" rel="noopener">
          <b-img
            :src="require('../assets/sqlLogo.png')"
            fluid
            alt="SQL Logo"
            width="80"
            height="80"
          ></b-img>
        </a>
      </li>
      <li>
        <a href="https://www.docker.com/" target="_blank" rel="noopener">
          <b-img
            :src="require('../assets/dockerLogo.png')"
            fluid
            alt="Docker Logo"
            width="70"
            height="70"
          ></b-img>
        </a>
      </li>
      <li>
        <a href="https://azure.microsoft.com/es-es/" target="_blank" rel="noopener">
          <b-img
            :src="require('../assets/azureLogo.png')"
            fluid
            alt="Azure Logo"
            width="70"
            height="70"
          ></b-img>
        </a>
      </li>
      <li>
        <a href="https://aws.amazon.com/" target="_blank" rel="noopener">
          <b-img
            :src="require('../assets/awsLogo.svg.png')"
            fluid
            alt="AWS Logo"
            width="70"
            height="70"
          ></b-img>
        </a>
      </li>
    </ul>
    <h3>Essential Links</h3>
    <p>TODO: like twitter, linkedin, github</p>
    <ul>
      <li>
        <a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a>
      </li>
      <li>
        <a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a>
      </li>
      <li>
        <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a>
      </li>
      <li>
        <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a>
      </li>
      <li>
        <a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a>
      </li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li>
        <a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a>
      </li>
      <li>
        <a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/vue-devtools#vue-devtools"
          target="_blank"
          rel="noopener"
        >vue-devtools</a>
      </li>
      <li>
        <a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a>
      </li>
      <li>
        <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
