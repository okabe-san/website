<template>
  <div>
    <h2></h2>
    <div class="container">
      <div class="info">
      </div>
      <div class="info">
      </div>
      <div class="info">
      </div>
      <div class="info">
      </div>
      <div class="info">
      </div>
      <div class="info">
      </div>
    </div>
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
  display: flex;
  flex-wrap: wrap;
  padding: 2rem 10%;
}
.info {
  box-sizing: border-box;
  width: 50%;
  height: 300px;
  border: 1px solid gray;
}
</style>
