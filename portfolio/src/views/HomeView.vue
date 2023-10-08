<template>
  <v-app :style="{ background: $vuetify.theme.themes.dark.background}">
    <navbar-component />
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
