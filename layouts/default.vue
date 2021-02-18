<template>
  <div class="container">
    <nuxt-link to="/" class="title text-left">Blog</nuxt-link>
    <ColorModePicker />
    <nuxt />
  </div>
</template>

<script>
import ColorModePicker from '~/components/general/ColorModePicker.vue'

export default {
  components: {
    ColorModePicker
  }
}
</script>
