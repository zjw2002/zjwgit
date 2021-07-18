<template>

   <div class="yemian">
  <top>

  </top>
    <MyItem></MyItem>
    </div>
 
</template>
 
<script>
 import top from './components/top.vue'
 import Myfooter from './components/Myfooter.vue'
 import MyItem from './components/MyItem.vue'
export default {
  name: 'App',
    data() {
    return {
      input: ''
    }
  },
  components:{
    top,Myfooter,MyItem
  }
}
</script>

<style>
*{
    padding: 0;
    margin: 0;
    background-color: white;
}
.yemian{
    width: 600px;
    height: 400px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    margin: 10% auto

  
}


</style>
