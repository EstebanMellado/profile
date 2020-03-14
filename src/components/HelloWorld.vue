<template>
  <div class="container">
    <h1>{{ msg }}</h1>
    <div class="row">
      <div class="column">
        <p>
          Born in the 90's and coding since 2017. Always worked in IT. My motivation
          are new challenges, always wants to learn new technologies.
        </p>
      </div>
      <div class="column">
        <p>
          When I am not coding I'm doing some sports or hanging out with friends or
          going to meetups to make networking and meet other developers.
        </p>
      </div>
      <div class="column">
        <p>
          In 2018 I became a speaker in some national and international tech events,
          this turns up something new in me and gave me lovely experiences on a
          stage sharing my knowledge.
        </p>
      </div>
    </div>
    <h3>Some of my skills</h3>
    <Skills />

    <h3>Essential Links</h3>
    <SocialNetworks />
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

* {
  box-sizing: border-box;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
