<template>
 <div class="banner">
   <video autoplay muted loop >
     <source src="../assets/mian.mp4">
   </video>

   <div class="Banner_tag has-text-centered">
      <h1 class="headLine" style="font-size: 60px">Enjoy Welding With JWelding</h1>
     <button class="button" style="font-size: 12px; margin-top: 15px">
       Shop Now
     </button>
   </div>

 </div>
</template>

<style scoped>
@import "bulma/css/bulma.min.css";


.banner{
  width: 100%;
  height: 70vh;
  position: relative;
  color: black;
}

video
{
  width: 100%;
  height: 70vh;
 object-fit: cover;

}

.Banner_tag
{

  position: absolute;
  padding: 50px;
  top: 22%;
  left: 50%;
  right: 0;
  transform: translateX(-50%);
  background-color: rgba(240, 240, 240, 0.6)


}

.button {
  padding: 1em 2em;
  border: none;
  border-radius: 5px;
  font-weight: bold;
  letter-spacing: 5px;
  text-transform: uppercase;
  color: #D71903;
  transition: all 1000ms;
  font-size: 15px;
  position: relative;
  overflow: hidden;
  outline: 2px solid #D71903;
}

button:hover {
  color: #D71903;
  transform: scale(1.1);
  outline: 2px solid #D71903;
  box-shadow: 4px 5px 17px -4px #D71903;
}

button::before {
  content: "";
  position: absolute;
  left: -50px;
  top: 0;
  width: 0;
  height: 100%;
  background-color: #D71903;
  transform: skewX(45deg);
  z-index: -1;
  transition: width 1000ms;
}

button:hover::before {
  width: 250%;
}

.headLine{
  font-size: 1.5rem;
}


@media only screen and (max-width: 600px) {
  .Banner_tag
  {
    width: 100%;
    right: 0;
  }
}

@media only screen and (max-width: 900px) {
  /*.Banner_tag*/
  /*{*/
  /*  width: 100%;*/
  /*  right: 0;*/
  /*}*/
}

</style>