<template>
  <nav class="main-nav">
    <router-link :to="{ name: 'Home'}" >Projects</router-link>
    <router-link :to="{ name: 'AddProject'}" >Add a new project</router-link>
  </nav>
</template>

<script>
export default {

}
</script>

<style>
.main-nav {
    text-align: center;
    margin: 40px auto;
  }
  .main-nav a{
    display: inline-block;
    text-decoration: none;
    margin: 0 10px;
    color: rgb(61, 57, 57);
    font-size: 18px;
    font-weight: bold;
  }
  a.router-link-active {
    border-bottom: 2px solid #00ce89;
    padding-bottom: 4px;
  }
</style>