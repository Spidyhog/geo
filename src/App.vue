<template>
  <div id="app">
    <Navbar/>
    <Footer/>
    <router-view/>
  </div>
</template>

<script>
import Navbar from '@/components/layout/Navbar'
import Footer from '@/components/layout/Footer'
export default {
  name: 'App',
  components:{
    Navbar,
    Footer
  }
}
</script>

<style>

</style>
