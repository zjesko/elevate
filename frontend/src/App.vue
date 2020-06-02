<template>
      <div id="app">
          <Navigation></Navigation>
        <router-view />
      </div>
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
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
body {
  padding-top: 80px;
}
</style>
