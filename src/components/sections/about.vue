<template>
  <div class="container">
    <div class="title">
      <div>
        <h1>ABOUT</h1>
      </div>
    </div>
    <div class="note">
      <div>
        <h3>
          I am a web developer and a former 3d artis.
        </h3>
        <h3>
          Outside of coding, I enjoy Colorado summer, ski, craft beer, and my new adventure scuba diving.
        </h3>
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
  font-size: 72px;
  color: #7997A1;
}
.container {
  display: flex;
  flex-wrap: wrap;
  box-sizing: border-box;
  min-height: 400px;
  padding: 2rem;
  background: rgba(0, 0, 0, 0.05);
}
.title, .note {
  display: flex;
  justify-content: center;
  align-items: center;
  word-wrap: break-word;
}
.title {
  width: 400px;
  border-right: 1px solid #fff;
}
.note {
  flex: 1;
}
@media (max-width: 850px) {
  .container {
    flex-direction: column;
  }
  .title {
    width: 100%;
    border: none;
  }
}
</style>
