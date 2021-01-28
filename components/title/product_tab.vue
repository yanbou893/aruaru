<template>
<div>
  <b-nav tabs>
    <b-nav-item active>Active</b-nav-item>
    <b-nav-item>Link</b-nav-item>
    <b-nav-item>Another Link</b-nav-item>
    <b-nav-item>Disabled</b-nav-item>
  </b-nav>
</div>
</template>

<script>
import product from '~/components/main/product_view.vue'
export default {
  components: {
    product
  }
}
</script>