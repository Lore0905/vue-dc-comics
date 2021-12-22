<template>
  <div id="app">

    <Header />
    <ComicsList />
    <Main />
    <Footer />
  </div>
</template>

<script>

import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
import ComicsList from "./components/ComicsList.vue";


export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
    ComicsList,

  },
};
</script>

<style lang="scss">
@import './style/variables.scss';
@import './style/general.scss';
@import './style/common.scss';
</style>
