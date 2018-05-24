<template>
  <div>
    <header>
      <nav>
      </nav>
      <h1>{{ msg }}</h1>
    </header>
    <content>
      <section>
      </section>
      <section>
      </section>
      <section>
      </section>
    </content>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'こんにちは。'
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
  background: rgba(0, 0, 0, 0.05);
}
section {
  height: 700px;
  background: linear-gradient(180deg, #fff, rgba(0, 0, 0, 0.05));
}
</style>
