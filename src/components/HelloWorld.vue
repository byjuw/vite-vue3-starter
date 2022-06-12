<script setup>
defineProps({
  msg: String
})
</script>

<template>
  <h2>{{ msg }}</h2>
</template>

<style scoped>
h2 {
  color: #42b983;
}
</style>
