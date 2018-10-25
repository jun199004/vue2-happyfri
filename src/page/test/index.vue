<template>
  <div id="components-demo">
    <buttoncounter></buttoncounter>
  </div>
</template>

<script>
  import buttoncounter from '../../components/buttoncounter'

  export default {
    name: "test",
    created(){
      //初始化信息
      //document.body.style.backgroundImage = 'url(./static/img/1-2.png)';
      document.body.style.background='#b3b2bc';
    }
  }
</script>

<style scoped>

</style>


