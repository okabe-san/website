<template>
  <div class="container">
    <img src="../../assets/images/graphics.png">
  </div>
</template>

<script>
export default {
  name: 'Modeling',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
.container {
  position: relative;
  overflow: hidden;
  height: 800px;
}
img {
  position: absolute;
  top: -9999px;
  bottom: -9999px;
  left: -9999px;
  right: -9999px;
  margin: auto;
  }
</style>
