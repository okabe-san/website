<template>
  <div class="container">

    <div class="title">
      <h1>embroidery ORDER</h1>
    </div>
    <div class="note">
      <div>
        <h3>
          An order form application for a small embroidery business. Using Vue.js.
        </h3>
        <h3>
          For a better user experience.
        </h3>
        <h3>
          * To design only for a desktop *
        </h3>
        <p><a
          href="https://github.com/okabe-san/esquire_order"
          target="_blank">
          https://github.com/okabe-san/esquire_order
        </a></p>
        <p><a
          href="http://order.customembellishment.com/#/"
          target="_blank">
          http://order.customembellishment.com/#/
        </a></p>
      </div>
    </div>
    <div class="title">
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
  padding: 4rem;
}
.title, .note {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  word-break: break-word;
}
.title {
  flex: 1;
}
.note {
  flex: 2;
  padding: 0 1rem;
}
img {
  max-width:100%;
  max-height:100%;
}
@media (max-width: 850px) {
  h1 {
    font-size: 40px;
  }
  .container {
    flex-direction: column;
  }
  .title {
    order: 1;
  }
  .note {
    order: 2;
    padding: 0;
  }
}
</style>
