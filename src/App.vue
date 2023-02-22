<template>
  <v-app>
    <v-main>
      <NavBar />
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/public/NavBar.vue'

export default {
  name: 'App',

  components: {
    HelloWorld,
    NavBar,
  },

  data: () => ({
    //
  }),
}
</script>
