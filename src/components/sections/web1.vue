<template>
  <div class="container">

    <div class="title">
    </div>
    <div class="note">
      <div>
        <h3>
          A single page application which uses AngularJS controllers and services.
        </h3>
        <h3>
          It is an everyday brain training game for everyone.
        </h3>
        <h3>
          * To design only for a mobile *
        </h3>
        <p><a
          href="https://github.com/okabe-san/ten-puzzle-front"
          target="_blank">
          https://github.com/okabe-san/ten-puzzle-front
        </a></p>
        <p><a
          href="https://ten-puzzle.firebaseapp.com/#/"
          target="_blank">
          https://ten-puzzle.firebaseapp.com/#/
        </a></p>
      </div>
    </div>
    <div class="title">
      <div>
        <h1>ten PUZZLE</h1>
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
h1 {
  font-size: 60px;
}
.container {
  display: flex;
  flex-wrap: wrap;
  box-sizing: border-box;
  height: 400px;
  padding: 2rem 4rem;
}
.title, .note {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  height: 100%;
}
.title {
  flex: 1;
}
.note {
  flex: 2;
}
img {
  max-width:100%;
  max-height:100%;
}
</style>
