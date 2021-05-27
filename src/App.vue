<template>
  <div id="Main">
    <TopNav></TopNav>
    <Slide></Slide>
    <Content4></Content4>
    <Content3></Content3>
    <Content2></Content2>
    <Content1></Content1>
    <Footer></Footer>
  </div>
</template>

<script>
import TopNav from './components/TopNav.vue'
import Slide from './components/Slide.vue'
import Content4 from './components/Content4.vue'
import Content3 from './components/Content3.vue'
import Content2 from './components/Content2.vue'
import Content1 from './components/Content1.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    TopNav,
    Slide,
    Content4,
    Content3,
    Content2,
    Content1,
    Footer
  }
}
</script>

<style>
  * {
    margin:0;
    box-sizing: border-box;
    padding: 0;
  }

  #Main{
    max-width: 1920px;
    width: 100%;
    
  }
</style>
