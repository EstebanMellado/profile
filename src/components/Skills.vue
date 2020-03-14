<template>
  <div>
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
  </div>
</template>

<script>
export default {
  name: "Skills"
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
li:hover {
  -webkit-box-shadow: 0 8px 6px -6px black;
  -moz-box-shadow: 0 8px 6px -6px black;
  box-shadow: 0 8px 6px -6px black;
  transform: scale(1.1);
}
</style>
