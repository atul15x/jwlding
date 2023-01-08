<template>
  <nav class="navbar  is-white" style="border-bottom: 5px solid #D71903">
    <!--logo-->
    <div class="navbar-brand">
      <a class="navbar-item">
        <img src="../assets/logo.jpg" alt="logo" style="max-height: 40px" class="px-2 py-2">
      </a>
      <a class="navbar-burger px-2 py-2" @click="navToggle">
          <span></span>
          <span></span>
          <span></span>
      </a>
    </div>

    <div class="navbar-menu" id="nav-links">
      <div class="navbar-start">
          <a href="" class="navbar-item is-active">Home</a>
          <a href="" class="navbar-item">Products</a>
          <a href="" class="navbar-item">About Us</a>
          <a href="" class="navbar-item">For Business</a>
          <a href="" class="navbar-item">Advantage</a>
          <a href="" class="navbar-item">Service</a>
           <a href="" class="navbar-item">Contact</a>
      </div>

      <div class="navbar-end">
        <div class="field is-grouped px-4 py-4">
          <p class="control">
            <input class="input" type="text" placeholder="Search Here">
          </p>
          <p class="control">
            <a class="button is-danger">
              Search
            </a>
          </p>
        </div>
      </div>

    </div>



  </nav>
</template>

<style scoped>
@import "bulma/css/bulma.min.css";

</style>

<script>
 export default{
   data(){
    return
     {

     }
   },
   methods:{
     navToggle(){
        const navbarMenu = document.querySelector('#nav-links')

        navbarMenu.classList.toggle('is-active')
     }
   }
 }
</script>