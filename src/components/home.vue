<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li>
        <a
          href="http://3dvisualizationtips.blogspot.com/"
          target="_blank">
          Blog
        </a>
      </li>
      <li>
        <a
          href="https://www.turbosquid.com/Search/Artists/3d-vis?referral=3d-vis"
          target="_blank">
          3d props
        </a>
      </li>
      <li>
        <p>A single page application which uses AngularJS controllers and services. It is an everyday brain training game for everyone.
        * To design only for a mobile *
        </p>
        <a
          href="https://github.com/okabe-san/ten-puzzle-front"
          target="_blank">
          https://github.com/okabe-san/ten-puzzle-front
        </a>
        <a
          href="https://ten-puzzle.firebaseapp.com/#/"
          target="_blank">
          https://ten-puzzle.firebaseapp.com
        </a>
      </li>
      <li>
      </li>
    </ul>
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
</style>
