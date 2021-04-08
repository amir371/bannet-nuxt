<template>
<div>
  <img  class="back" src="@/assets/img/arrowleft.png" alt="logoEmbajador">
  <div class="top">
    <h1>BANNET</h1>
    <p>فروشگاه هوشمند بنت</p>
  </div>
  <p class="center">کد ارسالی وارد نمایید</p>
  <p class="title5ragham">کد5رقمی به شماره شما پیامک شد</p>
  <div class="phone">
    <img src="@/assets/img/edit.png" alt="">
    <p>09370402434</p>
  </div>
  <div class="number5ragham">
    <p>2</p>
    <p>6</p>
    <p>9</p>
    <p>4</p>
    <p>5</p>
  </div>
  <div class="titlesunder">
    <div class="mojadadpayamak">ارسال مجدد پیامک</div>
    <div class="dontpayamak"> پیامکی دریافت نکرده اید؟</div>
  </div>
  <div class="button">
    <p>ارسال</p>
  </div>
</div>

</template>
<script>
export default {
}
</script>
<style lang="scss" scoped>
body{
  position: relative;
}
.back{
  position: fixed;
  left: 0;
  top: 0;
  padding: 10px;
  color: blueviolet;
}
.top {
  margin-top: 10rem;
  text-align: center;
}
.top h1{
  font-size: 30px;
  color: $third_text_color;
}
.top p{
  color: blueviolet;
}
.center {
  margin-top: 100px;
  text-align: center;
  font-size: 20px;
  color: $third_text_color;
}
.title5ragham{
  padding: 10px;
  color:#cdcdcd;
  text-align: center;
  font-size: 12px;
}

.phone{
  display: flex;
  border-radius: 20px;
  justify-content: center;
  background: rgba(137, 43, 226, 0.151);
  width: 35%;
  margin-left: auto;
  margin-right: auto;
  padding: 5px;
}
.phone img{
  width: 20px;
  height: 20px;
}
.phone p{
   color: rgb(137, 43, 226);
}
.number5ragham{
  display: flex;
  justify-content: center;
  margin-top: 20px;
}
.number5ragham p{
  margin-right: 5px;
   background: #F5F5F5;
   border-radius: 15px;
   width: 50px;
   height: 50px;
   color: $third_text_color;
   text-align: center;
   font-size: 30px;
}
.titlesunder{
  display: flex;
  justify-content: space-between;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
  margin-top: 10px;
  font-size: 10px;
}
.dontpayamak{
  color: $third_text_color;
}
.mojadadpayamak{
  color: blueviolet;
}

.button{
  position: fixed;
  bottom: 10px;
  right: 0;
  left: 0;
  margin-right: 20px;
  margin-left: 20px;
  border: 2px solid blueviolet;
  border-radius: 15px;
  background-color: blueviolet;
  color: white;
  text-align: center;
  padding: 10px;
}
</style>
