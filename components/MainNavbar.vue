
    <template>
  <nav>
<div class="d-flex align-items-center justify-content-between ">

<div class="d-flex">
  <div class="d-flex align-items-center">
  <img src="../static/images/logo.jpg" width="50px" height="50px"/>
<div  class="mx-3">
  <p>اللجنة الوطنية لمكافحة غسل الاموال وتمويل الارهاب</p>
  <p>National Anti-Money Laundering and Terrorism Financing Committee</p>

</div>
</div>
<div class="px-5">
  <ul class="nav nav-pills">
  <li class="nav-item">
    <a class="nav-link active" aria-current="page" href="#">home</a>
  </li>
  <li class="nav-item dropdown">
    <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">about us</a>
    <ul class="dropdown-menu">
      <li><a class="dropdown-item" href="#">Action</a></li>
      <li><a class="dropdown-item" href="#">Another action</a></li>
      <li><a class="dropdown-item" href="#">Something else here</a></li>
      <li><hr class="dropdown-divider"></li>
      <li><a class="dropdown-item" href="#">Separated link</a></li>
    </ul>
  </li>
  <li class="nav-item dropdown">
    <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">about us</a>
    <ul class="dropdown-menu">
      <li><a class="dropdown-item" href="#">Action</a></li>
      <li><a class="dropdown-item" href="#">Another action</a></li>
      <li><a class="dropdown-item" href="#">Something else here</a></li>
      <li><hr class="dropdown-divider"></li>
      <li><a class="dropdown-item" href="#">Separated link</a></li>
    </ul>
  </li>
  <li class="nav-item dropdown">
    <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">about us</a>
    <ul class="dropdown-menu">
      <li><a class="dropdown-item" href="#">Action</a></li>
      <li><a class="dropdown-item" href="#">Another action</a></li>
      <li><a class="dropdown-item" href="#">Something else here</a></li>
      <li><hr class="dropdown-divider"></li>
      <li><a class="dropdown-item" href="#">Separated link</a></li>
    </ul>
  </li>
</ul>
</div>
</div>
<div >
  <a href="#" class="mx-3">العربية</a>

  <svg xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M416 208c0 45.9-14.9 88.3-40 122.7L502.6 457.4c12.5 12.5 12.5 32.8 0 45.3s-32.8 12.5-45.3 0L330.7 376c-34.4 25.2-76.8 40-122.7 40C93.1 416 0 322.9 0 208S93.1 0 208 0S416 93.1 416 208zM208 352a144 144 0 1 0 0-288 144 144 0 1 0 0 288z"/></svg>
</div>
</div>
  </nav>
</template>


<script>
export default {

}
</script>


<style  scoped>

nav{
    padding:15px 40px;
    background-color:white;
    position: fixed;
    top: 0 !important;

    z-index: 50;
    width: 100%;
    box-shadow: 0px 15px 10px -15px #e4dada;

}
p{
  line-height: .5;
  color:green
}
a{
  color:black;
  text-transform: capitalize;
  }


    .active{
      color:green !important;
      background-color: white !important;
      text-decoration: underline;
    }

</style>
