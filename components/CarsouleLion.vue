<template>
 <div>
   <div id="carouselExampleCaptions" class="carousel slide">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="../static/images/slider3.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-block">
          <h2>Nation communication for Anti-Money Laundering</h2>
          <h2>& combating Financing of Terrorism</h2>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eius labore qui nobis facere expedita totam molestias
            possimus minima reiciendis excepturi Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eius labore qui nobis facere expedita totam molestias
            possimus minima reiciendis excepturi.</p>
            <a href="#">About As</a>

        </div>

      </div>
      <div class="carousel-item">
        <img src="../static/images/slider3.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h2>Nation communication for Anti-Money Laundering</h2>
          <h2>& combating Financing of Terrorism</h2>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eius labore qui nobis facere expedita totam molestias
            possimus minima reiciendis excepturi.</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="../static/images/slider3.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h2>Nation communication for Anti-Money Laundering</h2>
          <h2>& combating Financing of Terrorism</h2>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eius labore qui nobis facere expedita totam molestias
            possimus minima reiciendis excepturi.</p>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <div class="border border-1  border-white  rounded-circle p-2 d-flex justify-content-center ">

          <svg class='aria-hidden="true"'  xmlns="http://www.w3.org/2000/svg" fill='white' height="1.4em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M9.4 233.4c-12.5 12.5-12.5 32.8 0 45.3l160 160c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L109.2 288 416 288c17.7 0 32-14.3 32-32s-14.3-32-32-32l-306.7 0L214.6 118.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0l-160 160z"/></svg>

      </div>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <div class="border border-1 border-white rounded-circle p-2 d-flex justify-content-center ">
        <svg xmlns="http://www.w3.org/2000/svg" fill="white" height="1.4em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M438.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L338.8 224 32 224c-17.7 0-32 14.3-32 32s14.3 32 32 32l306.7 0L233.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160z"/></svg>

</div>
    </button>
  </div>
 </div>
</template>

<script>
export default {
  data() {
    return {

    };
  }
};
</script>
<style scoped>
.carousel-caption  {

position: absolute;
text-align: left;
    left: 6% !important;
    width: 50%;
    bottom: 26%;

}
h2{
  font-size: 2rem;
}
.carousel-caption p{
  color: #e3d8d8;
}

.carousel-item{
  height: 650px;
}
.carousel-control-prev, .carousel-control-next{
  opacity: 1 !important;
    transition: opacity 0.15s ease;

    padding-left: 50px;
    width: auto;
    bottom: 30%;

}

.carousel-control-prev{
  padding-left: 30px;
}
.carousel-control-next{
  padding-right: 30px;
}
/* dots */
.carousel-indicators{
  bottom: 30px;

}


.carousel-indicators button:not(:disabled),.carousel-indicators [type="button"]:not(:disabled),.carousel-indicators [type="reset"]:not(:disabled), .carousel-indicators [type="submit"]:not(:disabled) {
    cursor: pointer;
    background-color:  #f0f0f0;
    height: 10px;
    width: 10px;
    border: none;
    border-radius: 50%;
    margin-right: 10px;
}
a{
  background-color: white;
  padding:10px 25px;
  color:black;
  border-radius: 5px;
}

</style>
