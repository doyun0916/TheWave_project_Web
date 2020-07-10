<template>
  <div id="main_img1">
    <Header></Header>
  <div id="main_img2">
  </div>
  </div>
</template>

<script>
import Header from '../common/Header'
export default {
  name: 'HelloWorld',
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
   position: absolute;
   top:0;
   left:0;
 }
  #main_img2 {
    display: inline-block;
    width: 875px;
    height: 850px;
    background-image: url("./../assets/main2.png");
    background-size: cover;
    background-repeat: no-repeat;
    margin-left:655px;
  }
</style>
