<template>
  <transition name="modal">
    <div class="modal_mask">
      <div class="modal_container">

        <div class="modal_body">
          <div class="pdf">
            <pdf src="./static/Resume-Akiko Okabe.pdf"></pdf>
          </div>
        </div>

        <div class="modal_footer">
          <p class="button" @click="$emit('close')">
            CLOSE
          </p>
        </div>

      </div>
    </div>
  </transition>
</template>

<script>
import pdf from 'vue-pdf'

export default {
  name: 'Resume',
  components: {
    pdf
  }
}
</script>

<style scoped>
@import '../assets/style/modal_lib.css';
.pdf {
  height: 80vh;
  overflow: auto;
}
.button {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100px;
  height: 30px;
  float: right;
  margin-right: 1rem;
  background: #fff;
  border: 1px solid gray;
}
</style>
