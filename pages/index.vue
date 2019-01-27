<template>
  <div>
    <v-toolbar color="elevation-0" dense>
      <v-avatar size="36px">
        <img src="./../static/perfil_2.jpg" alt="Avatar">
      </v-avatar>
      <v-toolbar-title>My Devfolio</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat href="#home">Home</v-btn>
        <v-btn flat href="#about">About</v-btn>
        <v-btn flat>Certificates</v-btn>
        <v-btn flat>Projects</v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <full-page :options="options">
      <div id="home" class="section">
        <v-parallax dark src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg">
          <v-layout align-center column justify-center>
            <h1 class="display-2 font-weight-thin mb-3">Vuetify.js</h1>
            <h4 class="subheading">Build your application today!</h4>
          </v-layout>
        </v-parallax>
      </div>
      <div id="about" class="section">
        <v-parallax dark src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg">
          <v-layout align-center column justify-center>
            <h1 class="display-2 font-weight-thin mb-3">Vuetify.js</h1>
            <h4 class="subheading">Build your application today!</h4>
          </v-layout>
        </v-parallax>
      </div>
    </full-page>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      options: {
        controlArrows: true,
        scrollBar: true
      }
    }
  }
}
</script>
