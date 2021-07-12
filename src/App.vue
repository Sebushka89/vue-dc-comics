<template>
  <div id="app">
    <Header />
    <Main />
    <Stripes />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Stripes from './components/Stripes.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Stripes,
  }
}
</script>

<style lang="scss">
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

</style>
