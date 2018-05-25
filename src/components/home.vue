<template>
  <div>
    <header>
      <nav>
      </nav>
      <h1>こんにちは。</h1>
      <h3>(Hello)</h3>
    </header>
    <content>
      <web1></web1>
      <about></about>
      <web2></web2>
      <skills></skills>
    </content>
    <footer>
      <div class="title">
        <h2>THANK YOU FOR VISITING.</h2>
      </div>
      <div class="note">
        <a class="button">
          VIEW RESUME
        </a>
        <a class="button">
          GO TO GITHUB
        </a>
      </div>
      <div class="bottom">
        <p>
          aki0u0@gmail.com | Denver, CO
        </p>
        © 2018 Okabe
      </div>
    </footer>
  </div>
</template>

<script>
import web1 from './sections/web1.vue'
import web2 from './sections/web2.vue'
import about from './sections/about.vue'
import skills from './sections/skills.vue'

export default {
  name: 'Home',
  components: {
    web1,
    web2,
    about,
    skills
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
  display: flex;
  flex-wrap: wrap;
  box-sizing: border-box;
  padding: 5rem;
  background: gray;
}
.title, .note {
  display: flex;
  flex-direction: column;
}
.title {
  flex: 1;
  height: 100%;
}
.note {
  width: 500px;
}
.button {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 200px;
  height: 50px;
  margin-bottom: 1rem;
  background: #fff;
  font-size: 16px;
}
.bottom {
  padding-top: 6rem;
  width: 100%;
}
</style>
