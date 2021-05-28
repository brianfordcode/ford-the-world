<template>
   <div id="nav">

       <div class="content">

           
          <img src="/src/assets/main-logo.png" alt="logo">

          <div class="links">
            <router-link to="/">Home</router-link>
            <router-link to="/about">About</router-link> 
          </div>
            
       </div>
      

     
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>


#nav {
  background-color: rgba(255, 255, 255, 0.8);
  height: 50px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0px 2px 16px 0px rgba(0,0,0,0.15);
}

.content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 80%;
    max-width: 1000px;


}

#nav a {
  font-weight: bold;
  color: black;
  text-decoration: none;
  margin: 10px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>