<template>


    <navbar></navbar>
    
    <router-view/>
    
    <sitefooter></sitefooter>


</template>

<style>

* {
  margin: 0;
  padding: 0;
}

#app {
  font-family: courier;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-image: url('./assets/background-trans-large.png');
  background-size: 1200px auto;
  background-color: rgb(42, 88, 134);
}

</style>

<script>
import navbar from './components/navbar'
import sitefooter from './components/footer.vue'


export default {
  components: {
    navbar,
    sitefooter
  }
}
</script>

