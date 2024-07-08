<script setup lang="ts">
defineProps<{
  title: string
  subtitle: string
  image?: string
}>()
</script>

<template>
    <li>
      <h3>{{ title }}</h3>
      <p>{{ subtitle }}</p>
    </li>
</template>
  