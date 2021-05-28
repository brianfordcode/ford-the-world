<template>

<div class="container">
   <!-- <h1>map section</h1> -->
   <worldmap width="auto" height="100%"></worldmap>
</div>

  
</template>


<script>

import worldmap from './world-map'


export default {

components: {
    worldmap
}

   
}
</script>

<style scoped>

.container {
    height: 400px;
    background-color: rgba(255, 255, 255, 0.8);
    margin-top: 50px;
    width: 100%;
}

</style>