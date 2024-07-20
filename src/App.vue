<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
 
      <nav>

        <div className="desktopnavflex"> 

        <div className="desktopnavimg">
          <img src="./assets/Images/nazzamain.png"/> 
        </div> 

        <!-- <div>
        <RouterLink to="/"> Dashboard </RouterLink>
        <RouterLink to="/dashboard"> Dashboard </RouterLink>
        <RouterLink to="/about"> About us </RouterLink>
        <RouterLink to="/about"> How to trade </RouterLink>
        <RouterLink to="/contact"> Contact </RouterLink>
      </div>

      <div> 
        <RouterLink to="/login"> Login </RouterLink>
        <RouterLink to="/about"> Register </RouterLink>
      </div> -->

    </div>

    <!--  -->

    <div className="desktopnavflexx"> 

<div className="desktopnavimgg">
  <img src="./assets/Images/nazzamain.png"/> 
</div> 

<div className="navres"> 
  <i class="fa-solid fa-bars"></i>
</div>

</div>

    

      </nav>
  
  <RouterView />
</template>

<style src="./assets/style/style.css"> 
</style>



