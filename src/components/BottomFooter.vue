<template>
  <div id="footer" class="columns">
    <div class="column">Copyright</div>
    <div class="column">Copyright</div>
  </div>
</template>

<script>
export default {
  name: 'BottomFooter',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<style scoped>
#footer {
  background-color: rgb(90,74,66);
  color: #fff;
  min-height: 50px;
  position: absolute;
  bottom: 0px;
  left: 0px;
  right: 0px;
}
</style>
