<template>
  <div>
    <Header />
      <b-form-input v-model="text" placeholder="Enter your name"></b-form-input>
      <div class="mt-2">Value: {{ text }}</div>
    <Footer />
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'
export default {
  components: {
    Header,
    Footer,
  },
    data() {
      return {
        text: ''
      }
    }
  }
</script>