<template>
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
      <span class="subject">ARTIST</span>
      <div id="artist_box">
        <span><br>                       CONNECTION WITH
                         BEST EXPERTS LEADS
                     YOU TO SUCCESS</span>
      </div>
      <div class="morebox">
        <div class="expert">SEE EXPERTS</div>
      </div>
      <div class="morebox">
        <div class="partner">BECOME A PARTNER</div>
      </div>
    </div>
  </div>
</template>

<script>
import Header from '../common/Header'
export default {
  name: 'main',
  components: {Header},
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
   background-image: url("./../assets/main1.png");
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
    background-image: url("./../assets/main2.png");
    background-size: cover;
    background-repeat: no-repeat;
    margin-left:769px;
  }
  #wave {
    margin-top: 300px;
    -webkit-text-stroke: 1px white;
    font-family: "Freestyle Script";
    font-size: 83px;
    font-weight: 900;
    font-stretch: normal;
    font-style: normal;
    line-height: 0.24;
    letter-spacing: normal;
    text-align: left;
  }
  #wavesub {
    margin-left: 50px;
    margin-top: 43px;
    -webkit-text-stroke: 0.1px white;
    font-family: "FuturaRoundW01-Medium";
    font-size: 20px;
    font-weight: bold;
    font-stretch: normal;
    font-style: normal;
    line-height: 0.24;
    letter-spacing: normal;
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
    min-height: 6000px;
    background-color: #f3f3f3;
    position:absolute;
    top:0;
    left:0;
    z-index:-2;
  }
  #artist_img1{
    margin-top: 450px;
    display: inline-block;
    width: 1000px;
    height: 722px;
    background-image: url("./../assets/artist1.png");
    background-size: cover;
    background-repeat: no-repeat;
    left:0;
  }
  #artist_img2{
    margin-top: 450px;
    margin-left: -600px;
    position: absolute;
    display: inline-block;
    width: 600px;
    height: 450px;
    background-image: url("./../assets/artist2.png");
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
    font-family: FuturaRoundW01-Medium;
  }
  #artist_box{
    text-align:center;
    color:white;
    font-family: FuturaRoundW01-Medium;
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
    z-index:1;
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
</style>
