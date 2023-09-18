<template>
  <div class="content">
    <div style="width:70%;margin: auto;" class=" d-flex flex-column justify-content-center align-items-cente">
      <div class="d-flex   justify-content-between align-items-center">
      <h1>National Commitee Mandate</h1>

    </div>
    <VueSlickCarousel v-bind="setting" style="width:80%; margin:auto">
     <div v-for="i in 10" :key="i">
      <div style="opacity: .6;">module 0{{ i }}</div>
</div>


    </VueSlickCarousel>
   <div class="mt-5" style="width:70%;margin: auto;">
    <svg xmlns="http://www.w3.org/2000/svg" fill="white" height="4em" viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M149.1 64.8L138.7 96H64C28.7 96 0 124.7 0 160V416c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V160c0-35.3-28.7-64-64-64H373.3L362.9 64.8C356.4 45.2 338.1 32 317.4 32H194.6c-20.7 0-39 13.2-45.5 32.8zM256 192a96 96 0 1 1 0 192 96 96 0 1 1 0-192z"/></svg>
    <p >

      establish and develop and follow up on the implementation of
      a national strategy for prohibiliting and combating crimes of
      money launding, terrorism financing and fanancing activities involving weapons of mass destruction
      ,in coordination with the completent regulatory authorities .
    </p>
   </div>
    </div>
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



  "infinite": true,
  "slidesToShow": 6,
  "slidesToScroll": 1,
  "autoplay": true,
  "speed": 2000,
  // "autoplaySpeed": 2000,
  // "cssEase": "linear"
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
svg{
  padding: 10px;
  background-color: rgb(18, 56, 18);
  border-radius: 5px;
  margin-bottom: 20px;
}
.line{

  width:80px;
}
.content{
  margin-top:10px;
  margin-left: 30px;
  margin-right:30px;
  margin-bottom: 100px;
  background-color: rgb(18, 56, 18);
  color:white;
  height: 650px;
  display: flex;
  justify-content: center;
  align-items: center;

}
h1{
text-align: center;

margin: auto;
margin-bottom: 30px;
}
p{



  line-height: 2;
  text-align: left;
  margin: auto;
  padding-left: 5px;

}


</style>
