<template>

  <body>

    <navbar></navbar>
     <router-view/>
    
    <div class="content-pages">
      <mapsection></mapsection>
      <aboutsection></aboutsection>
      <gearsection></gearsection>
      <latestcontentsection></latestcontentsection>
    </div>
    
    <sitefooter></sitefooter>
  </body>

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
}

body {
  background-image: url('../src/assets/background-trans-large.png');
  background-size: 1200px auto;
  background-color: rgb(42, 88, 134);
}

.content-pages {
  display: flex;
  flex-direction: column;
  align-items: center;
  /* justify-content: space-around; */
}

/* .content-pages:first-child {
  padding-top: 10px;
} */

</style>

<script>
import navbar from './components/navbar.vue'
import gearsection from './components/gear-section.vue'
import latestcontentsection from './components/latest-content-section.vue'
import aboutsection from './components/about-me-section.vue'
import mapsection from './components/map-section.vue'
import sitefooter from './components/footer.vue'

export default {
  
  components: {
    navbar,
    mapsection,
    gearsection,
    latestcontentsection,
    aboutsection,
    sitefooter
  }
}
</script>
