<template>
  <div>
    <header>
      <h1>{{ msg }}</h1>
    </header>
    <content>

    </content>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'こんにちは'
    }
  }
}
</script>

<style scoped>
@import '../assets/style/main.css';
header {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 500px;
  background: rgba(0, 0, 0, 0.1);
}
</style>
