<template>

<div class="banner">
    <div class="content">
        <worldmap width="60%" height="100%"></worldmap>
        <h1>map section</h1> 
    </div>
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

.banner {
    width: 100%;
    background-color: rgba(255, 255, 255, 0.8);
}

.content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 0 auto;
    max-width: 1000px;
    min-width: 700px;
}

</style>