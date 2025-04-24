<template>
  <div>
    <h1>Welcome to the App</h1>
    <p>This is the default home page.</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'HomePage',
  layout: 'default'
})
</script>

<style scoped>
h1 {
  color: #333;
}
</style>
