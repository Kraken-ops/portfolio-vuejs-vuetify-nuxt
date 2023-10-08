<template>
  <v-app id="home" :style="{ background: $vuetify.theme.themes.dark.background}">
    <navbar-component />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="1b.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h3 class="red--text text-darken-4 top">Hello I am Priyanshu</h3>
          <h1 class="white--text">Front-end Developer</h1>
          <p class="grey--text">
            I am a computer science graduate working as a Front-end Developer.<br>
            My passion for technology and eagerness to learn new things has driven me to stay upto date with the
latest industry trends and tools. <br> I have experience working with popular web frameworks such as Vue, Nuxt, React
Express, and Node.js, and I am always looking for opportunities to expand my skillset. <br>
As a quick learner with a strong work ethic, I am confident that I can make a valuable contribution to your
team. I am excited about the opportunity to apply my skills and knowledge to real world projects, and I am eager to take on new challenges as a software developer.
          </p>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
  
</template>

<script>
import NavbarComponent from '../components/NavbarComponent.vue'

  export default {
    name: 'Home',

    components: {
        NavbarComponent,
    },
  }
</script>
<style scoped>
.top{
  margin-top: 180px;
}
</style>