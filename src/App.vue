<template>
  <div id="app">
    <h1>test</h1>
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from './components/SiteHeader.vue';
import Main from './components/SiteMain.vue';
import Footer from './components/SiteFooter.vue';

export default {
  name: 'app',
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style lang="scss">
// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
//   margin-top: 60px;

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

@import '../src/assets/scss/style.css';
</style>
