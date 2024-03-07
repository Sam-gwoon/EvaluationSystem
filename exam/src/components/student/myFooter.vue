<!--页脚部分-->
<template>
  <footer id="footer">
    <ul>
<!--      <li><a href="javascript:;">关于我们</a></li>-->
      <li><a href="javascript:;">AI人才知识能力评测系统 v1.0.3</a></li>
      <li>Copyright © 2024 </li>
      <li> 版权所有：人工智能教育学部</li>
    </ul>
  </footer>
</template>

<script>
export default {
  name: "myFooter"
}
</script>

<style scoped>
#footer a {
  color: #919698;
  font-size: 14px;
}
#footer {
  background-color: #eee;
}
#footer ul {
  margin-top: 40px;
  border-top: 1px solid #d5d5d5;
  display: flex;
  justify-content: center;
  height: 80px;
  line-height: 80px;
}
#footer ul li {
  color: #919698;
  font-size: 14px;
  margin-right: 20px;
}
</style>
