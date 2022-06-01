

<template>

  <body>
    <div class="text">
      <v-app id="inspire">
        <v-toolbar
          dark
          color="primary"
        >
          <v-toolbar-side-icon></v-toolbar-side-icon>
          <v-toolbar-title>Ellefanter?</v-toolbar-title>
        </v-toolbar>
      </v-app>
    </div>

    <div
      class="hello"
      :style="image"
    >

      <h3>twerkande elefant</h3>
      <img
        src="https://c.tenor.com/PpiijrtPd30AAAAM/elephant-dancing.gif"
        alt=""
      >

      <h3>elefant med converse</h3>
      <img
        src="https://media3.giphy.com/media/SWKyABQ08mbXW/giphy.gif"
        alt=""
      >

      <h3>joggande elefant</h3>
      <img
        src="https://thumbs.gfycat.com/CheerfulVengefulBronco-max-1mb.gif"
        alt=""
      >

      <h3>skrikande elefant</h3>
      <img
        src="https://i.gifer.com/Wllj.gif"
        alt=""
      >

      <h3>bebis elefant</h3>
      <img
        src="https://i.gifer.com/UpFg.gif"
        alt=""
      >

    </div>
    <div id="app">
      <span class="bg"></span>
      <v-app id="inspire">
        <!-- <v-toolbar
          dark
          color="primary"
        >
          <v-toolbar-side-icon></v-toolbar-side-icon>
          <v-toolbar-title class="white--text">Title</v-toolbar-title>
        </v-toolbar> -->
      </v-app>
    </div>
  </body>

</template>

<script>
export default {
  name: 'HelloWorld',
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
#app {
  font-family: Consolas, ui-monospace;

  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.text {
  font-size: 60px;
  font-family: monospace;
  text-align: center;
  color: rgb(99, 99, 99);
  /* background-color: green; */
}
.hello {
  background: rgba(0, 0, 0, 0.4)
    url("https://d1jyxxz9imt9yb.cloudfront.net/project/601/meta_image/mobile/Nania-whisty-projectpage.jpg");
  height: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-blend-mode: darken;
  color: #ffffff;
  font-family: monospace;
  font-size: 25px;
  font-variant: small-caps;
}
</style>


