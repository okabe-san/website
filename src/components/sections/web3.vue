<template>
  <div class="container">

    <div class="title">
    </div>
    <div class="note">
      <div>
        <h3>
          A CRUD application designed for a small business featuring different user views.
        </h3>
        <h3>
          It was a team collaboration project where each member developed the frontend and backend.
        </h3>
        <p><a
          href="https://github.com/okabe-san/tai_chi_studio_two.git"
          target="_blank">
          https://github.com/okabe-san/tai_chi_studio_two.git
        </a></p>
      </div>
    </div>
    <div class="title">
      <div>
        <h1>tai-chi</h1>
        <h1>STUDIO</h1>
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
  height: auto;
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
@media (max-width: 500px) {
  .title {
    order: 1;
  }
  .note {
    order: 2;
  }
}
</style>
