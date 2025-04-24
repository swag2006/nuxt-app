<template>
  <div>
    <h1>About Us</h1>
    <p>This is the about page.</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'AboutPage',
  layout: 'default'
})
</script>

<style scoped>
h1 {
  color: #333;
}
</style>
