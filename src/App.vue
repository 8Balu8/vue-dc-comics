<template>
  <div id="app">
    <HeaderMenu />
    <Main/>
    <PreFooter/>
  </div>
</template>

<script>
import HeaderMenu from "./components/HeaderMenu.vue";
import Main from "./components/Main.vue";
import PreFooter from "./components/PreFooter.vue";

export default {
  name: "App",
  components: {
    HeaderMenu,
    Main,
    PreFooter
  },
};
</script>

<style lang="scss">
@import './styles/general.scss';
</style>
