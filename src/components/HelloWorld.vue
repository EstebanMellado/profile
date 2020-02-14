<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Born in the 90's and coding since 2017. Always worked in IT. My motivation
      are new challenges, always wants to learn new technologies.
    </p>
    <p>
      When I am not coding I'm doing some sports or hanging out with friends or
      going to meetups to make networking and meet other developers.
    </p>
    <p>
      In 2018 I became a speaker in some national and international tech events,
      this turns up something new in me and gave me lovely experiences on a
      stage sharing my knowledge.
    </p>

    <h3>Some of my skills</h3>
    <Skills />

    <h3>Essential Links</h3>
    <SocialNetworks />

    <!-- <h3>Ecosystem</h3>
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
    </ul>-->
  </div>
</template>

<script>
import Skills from "@/components/Skills.vue";
import SocialNetworks from "@/components/SocialNetworks.vue";

export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  components: {
    Skills,
    SocialNetworks
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
</style>
