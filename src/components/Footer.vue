<template>
  <section class="section" style="background-color:#191305;">
    <div class="container">
        <div class="columns">
          <div class="column">
            <div class="logo_brand">
              <img src="../assets/logo2.jpg">
            </div>
            <div class="address"> <i class="fa-solid fa-location-dot"></i> No. 9, Huadong Road, Yaoguan Town, Changzhou, Jiangsu</div>
            <div class="address"> <i class="fa-solid fa-envelope"></i> official@j-welding.com</div>
            <div class="address"> <i class="fa-solid fa-phone"></i>  +86 13357889573</div>

            <div class="social_icon">
              <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
              <a href="#"><i class="fa-brands fa-youtube"></i></a>
              <a href="#"><i class="fa-brands fa-tiktok"></i></a>
              <a href="#"><i class="fa-brands fa-square-instagram"></i></a>
            </div>
          </div>

          <div class="column">
              <h1 class="is-size-1 has-text-white">Product</h1>

            <div class="footer_menu">
              <a href="#"> Mig Welding Torch</a>
              <a href="#"> Plasma Cutting Torch</a>
              <a href="#"> Tig Welding Torch</a>
              <a href="#"> Welding Machine</a>
              <a href="#"> Welding Accessories</a>
              <a href="#">Trafimet Type</a>
            </div>

          </div>

          <div class="column">
            <h1 class="is-size-1 has-text-white">Information</h1>

            <div class="footer_menu">
              <a href="#"> About Us</a>
              <a href="#">For Business</a>
              <a href="#"> Service</a>
              <a href="#"> Advantage</a>
              <a href="#"> OEM</a>
              <a href="#">Privacy Policy</a>
            </div>

          </div>

        </div>
    </div>
  </section>
</template>

<style scoped>
@import "bulma/css/bulma.min.css";
img
{
  width: 200px;
}

i{
  color: #D71903;
  margin-right: 5px;
}

.address{
  color: white;
  padding: 20px 0px ;
}

.social_icon i{
  font-size: 1.5rem;
  padding: 5px;
}

.footer_menu
{
  padding-top: 60px;
}

.footer_menu a{
  color: white;
  display: block;
  padding: 10px 0px;

}

.footer_menu a:hover
{
  color: #D71903;
}
</style>