<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Home msg="Welcome to fhrzdty31's GitHub Pages"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Home from '@/components/HomeComponents.vue'

export default {
  name: 'HomeView',
  components: {
    Home
  }
}
</script>
