<template>
  <div>
    <header>
      <nav>
      </nav>
      <h1>こんにちは。</h1>
      <h3>(Hello)</h3>
    </header>
    <content>
      <image1></image1>
      <about></about>
      <image2></image2>
      <skills></skills>
      <web1></web1>
      <web2></web2>
      <web3></web3>
    </content>
    <footer>
      <div class="title">
        <h2>THANK YOU FOR VISITING.</h2>
        <p>（またのお越しを楽しみにしています。）</p>
      </div>
      <div class="note">
        <span class="button resume" @click="close = !close">
          VIEW RESUME
        </span>
        <resume
          v-if="close"
          @close="close = false">
        </resume>
        <a
          class="button"
          href="https://github.com/okabe-san"
          target="_blank">
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
import image1 from './sections/image1.vue'
import image2 from './sections/image2.vue'
import about from './sections/about.vue'
import skills from './sections/skills.vue'
import web1 from './sections/web1.vue'
import web2 from './sections/web2.vue'
import web3 from './sections/web3.vue'
import resume from './resume.vue'

export default {
  name: 'Home',
  components: {
    image1,
    image2,
    about,
    skills,
    web1,
    web2,
    web3,
    resume
  },
  data () {
    return {
      close: false
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
  display: flex;
  flex-wrap: wrap;
  box-sizing: border-box;
  padding: 5rem;
  color: #fff;
  background: #2c3e50;
}
.title, .note {
  display: flex;
  flex-direction: column;
}
.title {
  flex: 2;
  height: 100%;
}
.note {
  flex: 1;
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
.resume {
  font-weight: 600;
  background: #ff5233;
  cursor: pointer;
}
.bottom {
  padding-top: 6rem;
  width: 100%;
}
@media (max-width: 850px) {
  footer {
    flex-direction: column;
  }
  .note {
    align-self: center;
  }
}
</style>
