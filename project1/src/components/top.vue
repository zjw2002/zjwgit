<template>

     <div class="shang">
        <i class="el-icon-close"></i>
        <i class="el-icon-minus"></i>
        <i class="el-icon-s-tools"></i>
        <i class="el-icon-message-solid"></i>
      <img :src="imgUrl">
        </div>
 
    
</template>

<script>
export default {
  name: 'top',
  data () {
    return {
      imgUrl:require("../assets/src=http___hbimg.b0.upaiyun.com_37318b89be659926747e6617dee077ad1f078be71bbf9-xyuVjP_fw658&refer=http___hbimg.b0.upaiyun.jpg")


    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
.shang{
   height: 40%;
    width: 100%;
    background-color: aqua;
    background-image: linear-gradient(45deg,rgb(17, 29, 192), rgba(30, 171, 236, 0));
    animation-name: example;
    animation-duration: 6s;
    animation-iteration-count: infinite;
}
@keyframes example {
    25% {background-color: rgb(80, 102, 221);}
    50% {background-color: rgba(71, 175, 207, 0);}
    75%{background-color:  rgb(211, 144, 194);}
    100% {background-color: rgba(154, 227, 240);}
  }
.xia{
    height: 60%;
    width: 100%;
    background-color: white;
    
}
img{
    margin-left: 40%;
    margin-top: 18%;
    height: 70px;
    width: 70px;

}
.el-icon-minus{
  height: 30px;
  width: 30px;
  color: white;
  float:right;
  background-color: rgba(30, 171, 236, 0);
}
.el-icon-s-tools{
  height: 30px;
  width: 30px;
  color: white;
    float:right;
  background-color: rgba(30, 171, 236, 0);
}
.el-icon-close{
  height: 30px;
  width: 30px;
  color: white;
    float:right;
  background-color: rgba(30, 171, 236, 0);
}
.el-icon-message-solid{
   height: 30px;
  width: 30px;
  color: white;
   float: left;
  background-color: rgba(30, 171, 236, 0);
}

</style>
