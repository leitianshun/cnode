<template>
    <div class="header">
      <router-link  :to="{name:'root'}">
        <img src="../assets/cnodejs_light.svg" alt="">
      </router-link>
    <a href="https://cnodejs.org/"> <i class="iconfont icon-sousuo"></i> </a>
    
        <input type="text" placeholder="搜索" v-focus class="iconfont icon-sousuo" />
     
    
      <ul>
        <li><a href="#">首页</a></li>
        <li><a href="#">新手入门</a></li>
        <li><a href="#">API</a></li>
        <li><a href="#">关于</a></li>
        <li><a href="#">注册</a></li>
        <li><a href="#">登录</a></li>
      </ul>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
.header{
  background-color:#3d3a3a ;
  height: 50px;
  
 
}
img{
  max-width: 120px;
  margin-left: 50px;
  margin-top: 10px;
}
  ul{
 
    list-style: none;
    float: right;
    margin: 4px;
  }
  li{
    display: inline-block;
    padding: 10px 15px;
  }
  a{
    text-decoration: none;
    color: #ccc;
    font-size: 14px;
    text-shadow: none;
  }
 input {
   display: flex;
   position: absolute;
  border-radius: 20px;
  margin-left:200px;
 margin-top: -23px;
 border: none;
 outline:none;
 color: black;
  }
  i {
    
    margin-left:180px;
   margin-top: 20px;
   z-index: 10;
   color: black;
  cursor: pointer;
  position: absolute;
  }
</style>
