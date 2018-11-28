<template>
  <section class="body">
    <nav>
      <h1 class="brand" id="href"><nuxt-link to ="/">Friendly angkor tuk tuk</nuxt-link></h1>
      <ul>
        <li><nuxt-link to ="/">Home</nuxt-link></li>
        <li><nuxt-link to ="About">About</nuxt-link></li>
        <li><nuxt-link to ="Prices">Prices</nuxt-link></li>
        <li><nuxt-link to ="Gallery">Gallery</nuxt-link></li>
      </ul>
    </nav>
  </section>
</template>

<script>
export default {

}
</script>

<style>
section{
  margin: 0;
  padding: 0;
}
nav{
  width: 100%;
  background: black;
  padding: 0 50px;
  box-sizing: border-box;
}
nav h1{
  margin: 0;
  padding: 0;
  float: left;
}

nav h1 a{
  font-size: 20px;
  color: #fff;
  text-decoration: none;
}
nav ul{
  margin: 0;
  padding: 0;
  float: right;
}

</style>
