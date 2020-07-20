<template>
  <div class="container">
  <div id="page">
    <div class="main">
      <div id="main_img1"></div>
      <Header></Header>
      <div id="main_img2">
        <div id="wave">The Wave</div>
        <div id="wavesub">Giving opportunities and support to those who want to express their talents</div>
        <div class="morebox">Learn more</div>
      </div>
    </div>
    <div class="artist">
      <div id="artist_img1"></div>
      <span id="artist_img2"></span>
      <span class="subject" style="margin-left: 1000px;">ARTIST</span>
      <div id="artist_box">
        <span><br>                      CONNECTION WITH
                         BEST EXPERTS LEADS
                    YOU TO SUCCESS</span>
      </div>
      <div class="morebox" style="margin-top: -120px; margin-left: 1100px; position: relative;">SEE EXPERTS</div>
      <div class="morebox" style="margin-left: 1100px; position: relative; width:190px;">BECOME A PARTNER</div>
    </div>
    <div class="sports">
      <div id="sports_img1"></div>
      <span id="sports_img2"></span>
      <span class="subject" style="margin-left:-1000px;">SPORTS</span>
      <div id="sports_box">
        <span><br>               EARN THE CHANCE
                 TO BE CHALLENGED</span>
      </div>
      <div class="morebox" style="margin-top:-120px; margin-left: 110px; position: relative;">SEE EXPERTS</div>
      <div class="morebox" style="position: relative; width:190px; margin-left: 110px;">BECOME A PARTNER</div>
    </div>
    <div class="business">
      <div id="business_img1"></div>
      <span id="business_img2"></span>
      <span id="business_subject"><br>BUSINESS</span>
      <div id="business_box">
        <span><br>          MEET CONSULTANTS
            WITH BEST EXPERIENCE</span>
      </div>
      <div class="morebox" style="background-color: white; color:black; margin-top:-150px; margin-left:650px; position: relative; font-weight: 600;">SEE EXPERTS</div>
      <div class="morebox" style="background-color: white; color:black; margin-left:650px; position: relative; width:190px; font-weight: 600;">BECOME A PARTNER</div>
    </div>
    <Footer></Footer>
  </div>
  </div>
</template>

<script>
import Header from '../common/Header'
import Footer from '../common/Footer'
export default {
  name: 'main',
  components: {Header, Footer},
  data () {
    return {
      msg: '...'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #main_img1 {
    display: inline-block;
    width: 875px;
    height: 850px;
    background-image: url("./../assets/main1.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    position:absolute;
    top:0;
    left:0;
    z-index:-1;
  }
  #main_img2 {
    display: inline-block;
    width: 750px;
    height: 707px;
    background-image: url("./../assets/main2.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    margin-left:769px;
  }
  #wave {
    color: black;
    margin-top: 300px;
    -webkit-text-stroke: 0.1px white;
    font-family: Fair Prosper;
    font-size: 83px;
    font-weight: 900;
    font-stretch: normal;
    font-style: normal;
    line-height: 0.24;
    letter-spacing: normal;
    text-align: left;
  }
  #wavesub {
    color: black;
    margin-left: 50px;
    margin-top: 43px;
    -webkit-text-stroke: 0.2px white;
    font-family: Arial;
    font-weight: 700;
    font-size: 17px;
    font-stretch: normal;
    font-style: normal;
    line-height: 0.24;
    text-align: left;
  }
  .morebox {
    text-align: center;
    color:white;
    font-family: "Arial Rounded MT Bold";
    margin-left: 50px;
    margin-top: 25px;
    width: 140px;
    height: 30px;
    border: solid 1px white;
    background-color: black;
  }
  #page {
    padding: 0;
    margin: 0;
    width: 1519px;
    height: 4700px;
    background-color: #f3f3f3;
    position:absolute;
    top:0;
    left:0;
    z-index:-2;
  }
  #artist_img1{
    margin-top: 450px;
    display: block;
    width: 1000px;
    height: 722px;
    background-image: url("./../assets/artist1.jpg");
    background-size: cover;
    background-repeat: no-repeat;
  }
  #artist_img2{
    margin-top: -723px;
    margin-left: -358px;
    display: inline-block;
    position:absolute;
    width: 600px;
    height: 450px;
    background-image: url("./../assets/artist2.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    z-index:2;
  }
  .subject{
    color:black;
    display:block;
    font-size: 40px;
    margin-left:1200px;
    margin-top: -640px;
    font-family: "Trebuchet MS";
  }
  #artist_box{
    text-align:center;
    color:white;
    font-family: "Trebuchet MS";
    width: 780px;
    height: 350px;
    opacity: 0.95;
    border: solid 1px #707070;
    background-color: #c74b4b;
    margin-left: 737px;
    margin-top: 100px;
    font-size: 25px;
    font-weight: 500;
    white-space: pre;
    line-height: 180%;
    position:relative;
    z-index:0;
  }
  .morebox .expert{
    margin-top:-150px;
    margin-left:1040px;
    width: 140px;
    height: 30px;
    border: solid 1px white;
    background-color: black;
    position:relative;
    z-index:2;
  }
  .morebox .partner{
    margin-top: -140px;
    margin-left:1040px;
    width: 190px;
    height: 30px;
    border: solid 1px white;
    background-color: black;
    position:relative;
    z-index:2;
  }
  #sports_img1{
    margin-top: 450px;
    display: inline-block;
    width: 1000px;
    height: 722px;
    background-image: url("./../assets/sports1.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    margin-left:519px;
  }
  #sports_img2{
    position: absolute;
    display: inline-block;
    width: 550px;
    height: 350px;
    background-image: url("./../assets/sports2.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    margin-left: -1150px;
    margin-top: 822px;
    z-index:2;
  }
  #sports_box{
    text-align:left;
    color:white;
    font-family: "Trebuchet MS";
    width: 650px;
    height: 295px;
    opacity: 0.95;
    border: solid 1px #707070;
    margin-left:0;
    margin-top: 100px;
    font-size: 25px;
    font-weight: 500;
    white-space: pre;
    line-height: 180%;
    position:relative;
    z-index:0;
    background-color: #4bb6c7;
  }
  #business_img1{
    margin-top: 650px;
    display: inline-block;
    width: 1000px;
    height: 722px;
    background-image: url("./../assets/business1.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    margin-left:519px;
  }
  #business_img2{
    position: absolute;
    display: inline-block;
    width: 700px;
    height: 500px;
    background-image: url("./../assets/business2.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    margin-left: -1518px;
    margin-top: 650px;
    z-index:2;
  }
  #business_box{
    text-align:left;
    color:white;
    font-family: "Trebuchet MS";
    width: 650px;
    height: 222px;
    opacity: 0.95;
    border: solid 1px #707070;
    margin-left:270px;
    margin-top: -228px;
    font-size: 25px;
    font-weight: 500;
    white-space: pre;
    line-height: 200%;
    position:relative;
    z-index:0;
    background-color: black;
  }
  #business_subject {
    text-align: center;
    color: black;
    font-family: "Trebuchet MS";
    width: 360px;
    height: 150px;
    border: solid 1px #f3f3f3;
    margin-left: -900px;
    margin-top: 600px;
    font-size: 40px;
    position: absolute;
    z-index: 2;
    background-color: #f3f3f3;
  }
  @font-face {
    font-family: Fair Prosper;
    src: url(../font/Fair-Prosper.eot) format('embedded-opentype'),
    url(../font/Fair-Prosper.woff) format('woff'),
    url(../font/Fair-Prosper.ttf) format('truetype');
  }
  .container {
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
  }
  @media (min-width: 768px) {
    .container {
      width: 750px;
    }
  }
  @media (min-width: 992px) {
    .container {
      width: 970px;
    }
  }
  @media (min-width: 1200px) {
    .container {
      width: 1170px;
    }
  }
</style>
