<template>
  <div id="app">
    <Header />
    <Main />
    <Stripes />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Stripes from './components/Stripes.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Stripes,
    Footer
  }
}
</script>

<style lang="scss">
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
.container{
    max-width: 1200px;
    margin: 0 auto;
}

</style>
