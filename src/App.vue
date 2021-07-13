<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Main :comics="comics"/>
    <Stripes />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Jumbotron from './components/Jumbotron.vue';
import Main from './components/Main.vue';
import Stripes from './components/Stripes.vue';
import Footer from './components/Footer.vue';
import comicsJson from './jsons/dc-comics.json';

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Main,
    Stripes,
    Footer
  },
  data: function() {
    return {
      comics: comicsJson,
    };
  },
}
</script>

<style lang="scss">
@import "./style/app.scss"

</style>
