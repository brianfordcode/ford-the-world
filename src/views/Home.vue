<template>
  <body>
      <div class="content-pages">
        <mapsection></mapsection>
        <aboutsection></aboutsection>
        <gearsection></gearsection>
        <latestcontentsection></latestcontentsection>
      </div>
</body>

</template>

<script>
import gearsection from '../components/gear-section.vue'
import latestcontentsection from '../components/latest-content-section.vue'
import aboutsection from '../components/about-me-section.vue'
import mapsection from '../components/map-section.vue'

export default {
  name: 'Home',
  components: {
    mapsection,
    gearsection,
    latestcontentsection,
    aboutsection
  }
}
</script>


<style scoped>

.content-pages {
  display: flex;
  flex-direction: column;
  align-items: center;
  /* justify-content: space-around; */
}

.content-pages > div:first-child {
  margin-top: 50px;
}

</style>