<template>
  <div class="container pt-5" id="slide">
     <div class="text-center"><a href="">Learn more about Mac Optimization </a></div>
    <div class="performanceBoost">
      <div class="performanceContent"> 
          <ul class="list-inline">
            <li class="p1"><img src="../assets/images/list01.png" alt="" srcset=""></li>
            <li class="p2"><img src="../assets/images/list02.png" alt="" srcset=""></li>
            <li class="p3"><img src="../assets/images/list03.png" alt="" srcset=""></li>
          </ul>
      </div>
      <div class="bottomChange">
          <ul class="list-inline clearFix">
            <li class="">
                <i class="icons01"></i>
                <strong>Turbo Boost</strong>
            </li>
              <li class="">
                <i class="icons02"></i>
                <strong>Memory Clean</strong>
            </li>
              <li class="">
                <i class="icons03"></i>
                <strong>Startup optimization</strong>
            </li>
          </ul>
          <div class="messges">
            <p>Your Mac will be dragged slowly if your Mac disk permission has been changed no matter by yourself or the third party apps. And what’s more, the cache produced by the third party apps, especially the iTunes and the media app will occupy large space of your disk. MacBooster can fix the disk permission issues and optimize your disk storage to boost your Mac to the peak performance.</p>
          </div>
    
        </div>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'slider',
  data() {
    return {
    
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.performanceBoost {
  width: 1046px;
  height: 678px;
  margin: 0 auto;
  margin-top: 40px;
  position: relative;
  overflow: hidden;
  
}
.performanceContent {
    position: absolute;
    width: 536px;
    height: 378px;
    top: 0;
    left: 50%;
    margin-left: -249px;
    
}
.p1 {
  position: absolute;
  top: 0;
  left: 0;
  width: 536px;
  height: 338px;
  transition: all .3s ease;
  transform:translate3d(-255px, 0, 0) scale(.81);
  -webkit-transform:translate3d(-255px, 0, 0) 
  scale(.81);opacity:.4;z-index:1;
}
.p2 {
  position: absolute;
  top: 0;
  left: 0;
  width: 536px;
  height: 338px;
  transition: all .3s ease;
  transform:translate3d(0, 0, 0) scale(1);
  -webkit-transform:translate3d(0, 0, 0) 
  scale(1);opacity:1;z-index:4;

}
.p3 {
  position: absolute;
  top: 0;
  left: 0;
  width: 536px;
  height: 338px;
  transition: all .3s ease;
  transform:translate3d(255px, 0, 0) scale(.81);
  -webkit-transform:translate3d(255px, 0, 0)
   scale(.81);opacity:.8;z-index:1s;
}
img {
  width: 100%;
  height: 100%;
  vertical-align: middle;
  display: inline-block;
  border-radius: 8px;
  box-shadow: 0 20px 27px 0 rgba(146,151,158,0.85);
}

.clearFix:before, .clearFix:after {
    clear: both;
    content: "\90";
    display: block;
    height: 0;
    visibility: hidden;
    font-size: 0;
    line-height: 0;
}
.bottomChange {
  width: 800px;
  margin: 0 auto;
  margin-top: 378px;
  text-align: center;

  .clearFix {
    padding-bottom: 20px;
    border-bottom: solid #e7e7e7 3px;
  }

  li {
    position: relative;
    float: left;
    width: 250px;
    font-size: 18px;
  }
}

.icons01 {
  background:  url('~@/assets/images/icon01-gray.png');
  display: block;
  width: 76px;
  height: 76px;
  height: 61px;
  margin: 0 auto;
  margin-bottom: 30px;
  background-position: 50% 50%;
  background-repeat: no-repeat;
  background-size: 76px;
}
.icons02 {
  background:  url('~@/assets/images/icon02-gray.png');
  display: block;
  width: 76px;
  height: 76px;
  height: 61px;
  margin: 0 auto;
  margin-bottom: 30px;
  background-position: 50% 50%;
  background-repeat: no-repeat;
  background-size: 76px;
}
.icons03 {
  background:  url('~@/assets/images/icon02-gray.png');
  display: block;
  width: 76px;
  height: 76px;
  height: 61px;
  margin: 0 auto;
  margin-bottom: 30px;
  background-position: 50% 50%;
  background-repeat: no-repeat;
  background-size: 76px;
}

p {
    font-size: 16px;
    line-height: 24px;
    color: #27313c;
}
</style>

