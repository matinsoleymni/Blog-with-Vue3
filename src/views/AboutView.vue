<template>
  <div class="about d-flex j-center align-item-c f-dir-col ">
    <div class="title">
      <h1 class="orange">About Matin Soleymani</h1>
    </div>
    <div class="aboutBody">
      <p class="t-align-center">Matin Soleymani Fullstack web Developer</p>
    </div>
    <div class="github">
      <a href="https://github.com/matinsoleymni">
        <img src="https://github-stats-alpha.vercel.app/api?username=matinsoleymni&cc=22272e&tc=37BCF6&ic=AE87FF&bc=AE87FF">
      </a><br>
      <a href="https://github.com/matinsoleymni">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=matinsoleymni&layout=compact&theme=dark&hide_border=true">
    </a>
    </div>
  </div>
</template>

<style lang="scss">
  .about {
    background-color: blanchedalmond;
    margin: 10px 50px;
    border-radius: 24px;
    .title {
      background-color: white;
      border-radius: 50px;
      padding: 15px;
      margin: 15px 0px;
      cursor: pointer;
      transition: all .5s;
      &:hover {
        transition: all .5s;
        transform: scale(0.9);
        text-transform: capitalize;
        background-color: transparent;
      }
    }
    .github {
      text-align: center;
      margin: 40px 0px;
      
      a {
        img {
          width: 85%;
        }
      }
    }
  }
</style>