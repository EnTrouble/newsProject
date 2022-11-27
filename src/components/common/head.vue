<template>
  <div class="head">
    <div class="head-wrapper">
      <img src="../../../photo/head-logo.png" height="42" alt="">
      <ul>
        <li><a class="active" href="javascript:;">首页</a></li>
        <li><a class="active" href="javascript:;">新闻中心</a></li>
        <li><a class="active" href="javascript:;">元宇宙会场</a></li>
        <li><a class="active" href="javascript:;">数字展厅</a></li>
        <li><a class="active" href="javascript:;">数字案例</a></li>
        <li><a class="active" href="javascript:;">云上论坛</a></li>
        <li><a class="active" href="javascript:;">全景地展</a></li>
        <li><a class="active" href="javascript:;">大会直播</a></li>
        <li><a class="active" href="javascript:;">参会攻略</a></li>
      </ul>
    </div>
  </div>
</template>
  
<script>
export default {
  name: 'Header',
  props: {
  }
}
</script>
  
<style scoped>
.head {
  text-align: left;
  background-color: #00359F;
  padding: 4px 0 4px 40px;
}
.head-wrapper{
  width: 1200px;
  display: flex;
  flex-direction: row;
  align-items: center;
}
img {
  display: block;
  float: left;
}

ul {
  list-style-type: none;
  margin: 0;
}

li {
  float: left;
  padding-left: 14px;
}

li a {
  display: block;
  color: white;
  text-align: center;
  text-decoration: none;
  padding-bottom: 3px;
  border-bottom: 3px solid transparent;
}

li a:hover {
  border-bottom: 3px solid #fff;
}
</style>
  