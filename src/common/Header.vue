<template>
  <div class="box">
    <div class="group">
      <span class="menu"><img class="logo" src='./../assets/logo1.png'></span>
      <span class="menu" style="margin-left:300px"> ABOUT US </span>
      <span class="menu dropdown" style="margin-left:23px;"> ARTIST
          <div class="dropcont">
            <a href="#"><br>Experts</a>
            <a href="#"><br>Activity</a>
          </div>
      </span>
      <span class="menu dropdown" style="margin-left:15px"> BUSINESS
        <div class="dropcont">
          <a href="#"><br>Experts</a>
          <a href="#"><br>Activity</a>
        </div>
      </span>
      <span class="menu dropdown" style="margin-left:15px"> SPORTS
        <div class="dropcont">
          <a href="#"><br>Experts</a>
          <a href="#"><br>Activity</a>
        </div>
      </span>
      <span class="menu" style="margin-left:15px"> PARTNERS </span>
      <span class="menu" style="margin-left:23px"> SUGGESTION </span>
      <span class="menu" style="margin-left:110px"> CONTACT </span>
      <div id="mySidenav" class="sidenav">
        <a href="javascript:void(0)" class="closebtn" @click="closeNav">&times;</a>
        <a href="#">About us</a>
        <a>Artist</a>
        <a href="#" style="font-size:13px;">   experts</a>
        <a href="#" style="font-size:13px;">   activity</a>
        <a>Business</a>
        <a href="#" style="font-size:13px;">   experts</a>
        <a href="#" style="font-size:13px;">   activity</a>
        <a>Sports</a>
        <a href="#" style="font-size:13px;">   experts</a>
        <a href="#" style="font-size:13px;">   activity</a>
        <a href="#">Partners</a>
        <a href="#">Suggestion</a>
        <a href="#">Contact</a>
      </div>
      <span class="menu" @click="openNav" ><img class="toggle" src='./../assets/menubar.png'></span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  methods: {
    openNav: function () {
      document.getElementById('mySidenav').style.width = '170px'
      document.getElementById('mySidenav').style.height = '767px'
    },
    closeNav: function () {
      document.getElementById('mySidenav').style.width = '0'
      document.getElementById('mySidenav').style.width = '0'
    }
  }
}
</script>

<style scoped>
  .dropcont {
    text-align: center;
    display: none;
    position: absolute;
    background-color: #f1f1f1;
    min-width: 50px;
    min-height: 100px;
    z-index: 5;
    margin-top: 7px;
    border-radius:10%;
  }
  .dropcont a {
    color: black;
    padding: 10px 16px;
    display: block;
  }
  .dropcont a:hover {background-color: #ddd;}
  .dropdown:hover .dropcont {display: block;}
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
  .sidenav {
    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    right: 0;
    background-color: #111;
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
  }
  .sidenav a {
    padding: 8px 8px 8px  32px;
    font-size: 16px;
    color: #818181;
    display: block;
    transition: 0.3s;
    text-align: left;
    white-space: pre;
  }
  .sidenav a:hover {
    color: #f1f1f1;
  }
  .sidenav .closebtn {
    position: absolute;
    top: 0;
    right: 25px;
    font-size: 36px;
    margin-left: 50px;
  }
  @media screen and (max-height: 450px) {
    .sidenav {padding-top: 15px;}
    .sidenav a {font-size: 18px;}
  }
</style>
