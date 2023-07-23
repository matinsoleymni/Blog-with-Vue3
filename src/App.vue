<template>
  <Header></Header>
  <router-view/>
</template>

<script>
  import Header from "./components/AppHeader.vue"
  export default {
    name: "App",
    components: {
      Header
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
