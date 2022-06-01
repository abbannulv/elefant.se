

<template>

  <body>
    <div id="app">
      <span class="bg"></span>
      <v-app id="inspire">
        <v-toolbar
          dark
          color="primary"
        >
          <v-toolbar-side-icon></v-toolbar-side-icon>
          <v-toolbar-title class="white--text">Ellefanter?</v-toolbar-title>
        </v-toolbar>
      </v-app>
    </div>
    <div
      class="hello"
      :style="{'background-image':'url(https://upload.wikimedia.org/wikipedia/commons/thumb/3/37/African_Bush_Elephant.jpg/640px-African_Bush_Elephant.jpg)'}"
    >
      <!-- <h1>{{ msg }}</h1> -->
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
.bg {
  width: 100%;
  height: 100%;
  position: abs;
  top: 0;
  left: 0;
  background: url("https://upload.wikimedia.org/wikipedia/commons/thumb/3/37/African_Bush_Elephant.jpg/640px-African_Bush_Elephant.jpg")
    no-repeat center center;
  background-size: cover;
  /* background-color: red; */
  transform: scale(1.1);
}
</style>
