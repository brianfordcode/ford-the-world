<template>

    <div class="banner">
        <div class="content">
            <worldmap width="600px" height="100%"></worldmap>
            <h1>Where I've Been</h1> 
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
    background-color: rgba(255, 255, 255, 0.7);
}

.content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 0 auto;
    width: 80%;
    max-width: 1000px;
    min-width: 700px;
    /* border: 1px solid blue; */
}


</style>