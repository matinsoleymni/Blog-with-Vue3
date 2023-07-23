<template>
  <div class="home p-10 d-flex j-center align-item-c">
    <main class="">
      <div class="title">
        <h1>Welcome To Blog :)</h1>
        <p>This Blog Just for Learn Vue.JS</p>
      
        <div class="d-flex j-evenly mt-20">
          <span><a href="https://github.com/matinsoleymni">Github</a></span>
          <span><a href="mailto: matinsoleymni@gmail.com">Mail</a></span>
          <span><a href="https://blokchainology.com">Site</a></span>
        </div>
      </div>
        
    </main>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style lang="scss">

  .home {
    background-color: bisque;
    margin: 10px 50px;
    border-radius: 15px;
  
    span {
      a {
        color: cadetblue;
        text-decoration: none;
        &:hover {
          color: rgb(98, 226, 98);
        }
      }
    }
  }
</style>