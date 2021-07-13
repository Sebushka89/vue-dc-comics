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
@import "./style/app.scss"

</style>
