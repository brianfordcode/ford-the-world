<template>

<div class="banner">

    <div class="content">
        
        <img class="head-shot" src="../assets/head-shot.jpg" alt="head-shot">  
        
        <div class="text">
            <h1>About Me</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris 
            nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor 
            in reprehenderit in voluptate velit esse cillum dolore eu fugiat 
            nulla pariatur. Excepteur sint occaecat cupidatat non proident, 
            sunt in culpa qui officia deserunt mollit anim id est laborum.
            <br>
            <br>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris 
            nisi. Sunt in culpa qui officia deserunt mollit.
            </p>
        </div>
    </div>
    
</div>

  
</template>

<script>
export default {

}
</script>

<style scoped>

.banner {
    width: 100%;
}

.content {
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 40px auto;
    width: 80%;
    max-width: 1000px;
    min-width: 700px;
}

.head-shot {
    height: 300px;
    width: auto;
    box-shadow: 3px 3px 10px rgba(0,0,0,.5);
    border-radius: 8px;
}

.text {
    /* border: 1px solid pink; */
    padding-left: 5%;
}

h1 {
    padding-bottom: 10px;
}


</style>