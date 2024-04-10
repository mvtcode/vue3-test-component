<template>
  <button> {{ name }} </button>
</template>

<script setup lang="ts">
defineProps<{ name: string }>()

</script>

<style scoped>
</style>
