<template>
  <div class="home">
    <svg-icon icon-class="Addheart" class="logo"  />
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style media="screen">
    .logo{
      font-size: 10em;
    }
</style>
