<script setup lang="ts">
  interface Message {
    content: string
  }

  const message = defineProps<Message>()
</script>

<template>
  <h1>Hello {{ message.content }}</h1>
</template>
