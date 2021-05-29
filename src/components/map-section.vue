<template>

<div class="banner">
    <div class="container">
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
    height: 375px;
}

.container {
    height: 400px;
    /* background-color: rgba(255, 255, 255, 0.8); */
    /* margin-top: 50px; */
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: auto;
    max-width: 1000px;
}

.content {
    width: calc();
}

</style>