<template>
  <div id="app">
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

/* resete rules */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "Greta Sans Condensed Bold","Greta Sans Bold",Arial,sans-serif;
}

/* palette colori */
:root {
    --brand_blue: #0282F9;
    --brand_black: #1C1C1C;
    --brand_dark_gray: #303030;
    --brand_light_gray: #797979;
}

// columns
.main_margin {
  width: 80%;
  margin: auto;
}

.container .row {
    display: flex;
}

// selected items
.active {
  border-bottom: 5px solid var(--brand_blue);
  a {
    color: var(--brand_blue)
  }
}

@import '../src/assets/scss/style.css';
</style>
