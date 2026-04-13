<template>
  <div class="screen"></div>
</template>

<script setup lang="ts">
  definePageMeta({
    middleware: ['redirect-login']
  })
</script>
