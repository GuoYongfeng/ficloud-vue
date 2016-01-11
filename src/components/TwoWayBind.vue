<template>
  <p>{{ message }}</p>
  <input v-model="message">
</template>

<script>
  export default {
    data () {
      return {
        message: 'Hello'
      }
    }
  }
</script>
