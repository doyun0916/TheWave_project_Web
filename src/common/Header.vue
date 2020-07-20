<template>
  <div class="box">
    <div class="group">
      <span class="menu"><img class="logo" src='./../assets/logo1.png'></span>
      <span class="menu" style="margin-left:300px"> ABOUT US </span>
      <span class="menu" style="margin-left:23px"> ARTIST </span>
      <span class="menu" style="margin-left:15px"> BUSINESS </span>
      <span class="menu" style="margin-left:15px"> SPORTS </span>
      <span class="menu" style="margin-left:15px"> PARTNERS </span>
      <span class="menu" style="margin-left:23px"> SUGGESTION </span>
      <span class="menu" style="margin-left:110px"> CONTACT </span>
      <span class="menu"><img class="toggle" src='./../assets/menubar.png'></span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
  .box {
    margin-top: 80px;
    margin-left: -10px;
    width: 1529px;
    height: 60px;
    border: solid 1.5px #c3c3b7;
    border-right:0;
    border-left:0;
  }
  .menu {
    width: 80px;
    height: 24px;
    font-family: Trebuchet MS;
    font-weight: 100;
    font-size: 13px;
    -webkit-text-stroke: 1.3px black;
    font-style: normal;
    line-height: 0.67;
    display: inline-block;
  }
  .group {
    padding-left: 250px;
    padding-top: 10px;
  }
  .toggle {
    width:37px;
    height:37px;
    display: block;
  }
  .logo {
    width: 100px;
    height: 100px;
    display: block;
    border-radius:50%;
    margin-top: -30px;
    opacity: 0.75;
  }
</style>
