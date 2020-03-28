<template>
  <div id="app">
    <Nav />
  </div>
</template>

<script>
import Nav from "./components/Nav/Nav.vue";

export default {
  name: "App",
  components: {
    Nav
  }
};
</script>

<style lang="scss">
  @import "/assets/sass/generics";
  @import '~bootstrap/scss/bootstrap';
  @import '~bootstrap-vue/src/index.scss';
</style>
