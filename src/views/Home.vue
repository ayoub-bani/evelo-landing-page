<template>
  <div>
    <Navbar></Navbar>
    <Hero></Hero>
    <Main></Main>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '../components/Navbar.vue'
import Hero from '../components/Hero.vue'
import Main from '../components/Main.vue'

export default {
  name: 'Home',
  components: {
    Navbar,
    Hero,
    Main
  }
}

</script>
