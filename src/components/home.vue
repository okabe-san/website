<template>
  <div>
    <header>
      <nav>
      </nav>
      <h1>{{ msg }}</h1>
    </header>
    <content>
      <web1></web1>
      <web2></web2>
      <links></links>
      <modeling></modeling>
    </content>
    <about></about>
    <footer>
      <div class="bottom">
        © 2018 Okabe
      </div>
    </footer>
  </div>
</template>

<script>
import web1 from './sections/web1.vue'
import web2 from './sections/web2.vue'
import links from './sections/links.vue'
import modeling from './sections/modeling.vue'
import about from './sections/about.vue'

export default {
  name: 'Home',
  components: {
    web1,
    web2,
    links,
    modeling,
    about
  },
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
footer {
  position: relative;
  height: 300px;
}
.bottom {
  position: absolute;
  bottom: 2rem;
  width: 100%;
}
</style>
