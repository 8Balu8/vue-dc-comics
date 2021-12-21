<template>
  <div id="app">
    <HeaderMenu />
    <Banner/>
    <Main/>
    <PreFooter/>
    <Footer/>
    <PostFooter/>
  </div>
</template>

<script>
import HeaderMenu from "./components/HeaderMenu.vue";
import Main from "./components/Main.vue";
import PreFooter from "./components/PreFooter.vue";
import Footer from "./components/Footer.vue";
import PostFooter from "./components/PostFooter.vue";
import Banner from "./components/Banner.vue";

export default {
  name: "App",
  components: {
    HeaderMenu,
    Main,
    PreFooter,
    Footer,
    PostFooter,
    Banner
  },
};
</script>

<style lang="scss">
@import './styles/general.scss';
</style>
