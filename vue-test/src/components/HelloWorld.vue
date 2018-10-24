<template>
  <div class="hello">
    <h2 v-bind:title="toast">{{msg}}</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '页面加载于 ' + new Date().toLocaleString(),
      toast: '鼠标放置在这里的提示'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
h1, h2 {
  font-weight: normal;
  font-size: 24px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
$bgColor:#e3e3e3;
body{
  background: $bgColor;
}
</style>
