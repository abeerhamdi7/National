<template>
  <div class="content">
    <div class="d-flex   justify-content-between align-items-center">
      <h1>Strategic</h1>
   <div class="d-flex ">
    <div  class="border border-1 mx-2 rounded-circle p-2 d-flex justify-content-center ">

<svg class='aria-hidden="true"'  xmlns="http://www.w3.org/2000/svg" fill='gray' height="1.4em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M9.4 233.4c-12.5 12.5-12.5 32.8 0 45.3l160 160c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L109.2 288 416 288c17.7 0 32-14.3 32-32s-14.3-32-32-32l-306.7 0L214.6 118.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0l-160 160z"/></svg>

</div>
      <div class="border border-1  rounded-circle  d-flex justify-content-center p-2">
        <svg xmlns="http://www.w3.org/2000/svg" fill="gray"  height="1.4em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M438.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L338.8 224 32 224c-17.7 0-32 14.3-32 32s14.3 32 32 32l306.7 0L233.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160z"/></svg>

</div>
   </div>
    </div>
    <VueSlickCarousel v-bind="setting">
     <div v-for="i in 10" :key="i">
      <div class="card">
      <div class="card-body">
        <svg xmlns="http://www.w3.org/2000/svg" height="3em" fill="white" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M448 80v48c0 44.2-100.3 80-224 80S0 172.2 0 128V80C0 35.8 100.3 0 224 0S448 35.8 448 80zM393.2 214.7c20.8-7.4 39.9-16.9 54.8-28.6V288c0 44.2-100.3 80-224 80S0 332.2 0 288V186.1c14.9 11.8 34 21.2 54.8 28.6C99.7 230.7 159.5 240 224 240s124.3-9.3 169.2-25.3zM0 346.1c14.9 11.8 34 21.2 54.8 28.6C99.7 390.7 159.5 400 224 400s124.3-9.3 169.2-25.3c20.8-7.4 39.9-16.9 54.8-28.6V432c0 44.2-100.3 80-224 80S0 476.2 0 432V346.1z"/></svg>
        <h1 class="card-title">Development</h1>
        <div class="line"></div>
        <p class="card-text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Maxime eveniet debitis, voluptas ipsam ipsum sit.
        </p>

      </div>
    </div>
</div>

     >
    </VueSlickCarousel>
  </div>
</template>


<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

  export default {

    data(){
      return {
      setting:{

   "arrows": false,

  "infinite": true,
  "slidesToShow": 3,
  "slidesToScroll": 1,
  "autoplay": true,
  "speed": 2000,
  "autoplaySpeed": 2000,
  "cssEase": "linear"
    }}},

    components: { VueSlickCarousel },
  }
</script>
<style scoped>
.card{

  margin-right:30px;
  background-color: rgb(237, 241, 191) !important;
  padding: 30px;
  border:none
}
.card svg{
  padding: 10px;
  background-color: rgb(18, 56, 18);
  border-radius: 5px;
  margin-bottom: 20px;
}
.line{
  border-bottom: 3px solid;
  width:80px;
}
.content{
  margin-top:10px;
  margin-left: 30px;
  margin-right:30px;
  margin-bottom: 100px;

}
p{
  margin-top:15px;
  font-weight: bold;
}

</style>
