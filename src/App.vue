<template>
  <Header></Header>
  <router-view/>
  <Footer></Footer>
</template>

<script>
  import Header from "./components/AppHeader.vue"
  import Footer from "./components/AppFooter.vue"
  export default {
    name: "App",
    components: {
      Header,
      Footer
    }
  }
</script>
<style lang="scss">
* {
  margin: 0;
  padding: 0;
  font-family: Fira code;
  font-weight: 900;
}
</style>
