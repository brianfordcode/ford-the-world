<template>
   <div id="nav">

       <div class="content">

        <router-link to="/">
          <img class="logo" src="../assets/logo.png" alt="logo">
        </router-link>
          

          <div class="links">
            <router-link to="/">Home</router-link> 
            <router-link to="/countries">Countries</router-link> 
            <router-link to="/contact">Contact</router-link> 
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
  background-color: rgb(252, 252, 252);
  /* background-color: rgba(255, 255, 255, 0.8); */
  height: 70px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0px 2px 16px 0px rgba(0,0,0,0.15);
}

.logo {
    height: 60px;
    width: auto;
}

.content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 80%;
    max-width: 1000px;
}

#nav a {
  color: black;
  text-decoration: none;
  margin-left: 30px;
}

#nav a.router-link-exact-active {
  color: rgb(42, 88, 134);
}
</style>