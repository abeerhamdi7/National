<template>
 <div class="content">
  <div class="contentImg">
    <div >
      <h2> The Establishment</h2>
      <div class="line"></div>
<p>
Lorem ipsum dolor sit amet consectetur
 adipisicing elit. Corporis nobis tempora
  magnam, nulla recusandae vel officia earum officiis provident maiores eveniet a. Officia consequatur soluta inventore dolor velit tempore accusantium voluptate eaque, ullam, magnam repudiandae non nobis! Quam incidunt, quasi nostrum aliquam recusandae
 natus aut laboriosam maiores dolor aliquid impedit!
</p>
    </div>
    <!-- <img src="../static//images/house.jpg"> -->
  </div>

 </div>
</template>
<style scoped>
.content{
  margin-top:10px;
  margin-left: 30px;
  margin-right:30px;
}
.contentImg{


  background-image: url('../static/images/houses.jpg');
  width: 100%;
  height: 600px;
  background-repeat: no-repeat;
  background-position:center;
  background-size: cover;
  display: flex;
flex-direction: column;
  justify-content: center;
  align-items: center;
}
p,h2{
width: 50%;
margin: auto;
text-align: center;
}

h2{
  font-size: 2rem;
  color:white;

  padding-bottom:20px
}
 p{
  color: #fff;
}
.line{
  border-bottom: 3px solid white;
  width: 200px;
  margin: auto;
  margin-bottom: 20px;
}
</style>
