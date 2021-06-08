<template>
  <div id="app">
    <h1>Calculadora Consórcio</h1>
    <Main />
    <Footer />
  </div>
</template>

<script>
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Main,
    Footer
  }
}
</script>

<style lang="scss">
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
    padding: 0 0.5em;

    h1 {
      font-size: 2em;
      font-weight: bolder;
      margin: 0.7em 0;
    }

    h2 {
      font-size: 1.5em;
      font-weight: bolder;
      margin: 0.8em 0;
    }
}
</style>
