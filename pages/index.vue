<template>
<div>
  <img  class="back" src="@/assets/img/arrowleft.png" alt="logoEmbajador">
  <div class="center">
    <h1>BANNET</h1>
    <p>فروشگاه هوشمند بنت</p>
  </div>
  <div class="inputnumber">
    <p>:شماره موبایل</p>
    <div >
      <input type="text" placeholder="091******">

    </div>
  </div>
  <p class="ghanin">مطالعه قوانین و مقررات</p>
  <div class="button">
    <NuxtLink to="/about">دریافت کد</NuxtLink>
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
.center {
  margin-top: 10rem;
  text-align: center;
}
.center h1{
  font-size: 30px;
}
.center p{
  color: blueviolet;
}
.inputnumber {
  margin-top: 100px;
  margin-right: 20px;
  margin-left: 20px;
}
.inputnumber p{
  text-align: right;
  color: $third_text_color;
}
.inputnumber div{
   border: 2px solid rgb(245, 245, 245);
  padding: 10px;
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
  text-align: right;
}
.ghanin{
  position: fixed;
  bottom: 70px;
  right: 0;
  left: 0;
  text-align: center;
  color: $third_text_color;
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
