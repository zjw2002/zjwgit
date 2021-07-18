<template>
   <div class="xia">
            <div class="kuang">
            <input type="password" placeholder="QQ号码/手机/邮箱">
            <input type="password" placeholder="密码">
         <div class="Radio">
             <el-radio v-model="radio" label="1">自动登录</el-radio>
             <el-radio v-model="radio" label="2">记住密码</el-radio>
             <el-link href="https://element.eleme.io" target="_blank">找回密码</el-link>
         </div>
          <el-button  class="login">登录</el-button>
        </div>
        </div>
</template>

<script>
export default {
  name: 'MyItem',
  data () {
    return {
  
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.kuang{
  padding-top: 3%;
}
input{
 
    height: 30px;
    width: 300px;
    margin-left: 25%;
    background:none;  
	outline:none;  
    margin-top: 5px;
	border-bottom:1px solid #ccc;
    border-top: none;
    border-left: none;
    border-right: none;
}
input:focus{   
	border:none;
}
.Radio {
  padding-left: -10px;
  color: rgb(41, 42, 43);
  text-align: center;
 
}
.login{
width: 300px;
margin-left:150px ;
margin-top:20px ;
color:blue;
background-color: rgb(0, 132, 255);
}
</style>
