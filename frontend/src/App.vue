<template>
  <v-app>
    <v-content>
      <div id="app">
          <Navigation></Navigation>
        <router-view />
      </div>
    </v-content>
  </v-app>
</template>

<script>
import Navigation from './components/Navigation'
export default {
  name: 'App',
  components: {
    'Navigation': Navigation
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
body {
  padding-top: 80px;
}
</style>
