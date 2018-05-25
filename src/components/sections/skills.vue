<template>
  <div class="container">
    <div class="info_wapper">
      <div class="info">
        <h2>LANGUAGES</h2>
          <p>JavaScript</p>
          <p>Vue.js</p>
          <p>Node.js</p>
          <p>RUST</p>
          <p>postgreSQL</p>
          <p>HTML5</p>
          <p>CSS3</p>
      </div>
    </div>
    <div class="info_wapper">
      <div class="info">
        <h2>TOOLS</h2>
          <p>Git/Github</p>
          <p>Command Line</p>
          <p>Bootstrap</p>
          <p>WordPress</p>
      </div>
    </div>
    <div class="info_wapper">
      <div class="info">
        <h2>TECHNIQUES</h2>
          <p>Responsive Design</p>
          <p>API Integration</p>
          <p>Agile Development</p>
      </div>
    </div>
    <div class="info_wapper">
      <div class="info">
        <h2>DESIGN</h2>
          <p>Photoshop</p>
          <p>After Effects</p>
          <p>3ds max</p>
      </div>
    </div>
    <div class="info_wapper">
      <div class="info">
        <h2>EXTRA SKILL</h2>
          <p>Bilingual</p>
          <p>Japanese/English</p>
      </div>
    </div>
    <div class="info_wapper">
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
  padding: 8rem 18%;
  background: linear-gradient(180deg, rgba(0, 0, 0, 0.02), rgba(0, 0, 0, 0.08));
}
.info_wapper {
  box-sizing: border-box;
  width: 50%;
}
.info {
  box-sizing: border-box;
  width: 100%;
  height: 100%;
  padding: 4rem 0;
  border: 1px solid #fff;
  background: rgba(0, 0, 0, 0.2);
}
</style>
