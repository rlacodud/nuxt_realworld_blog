<template>
  <div class="tag" :class="{has_bg : hasBg}">
    <nuxt-link to="/">
      <span>{{title}}</span>
    </nuxt-link>
  </div>
</template>

<script setup>
defineProps({
  title: String,
  hasBg: {
    type: Boolean,
    default: false
  }
})
</script>

<style scoped>

</style>