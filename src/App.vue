<script setup lang="ts">
import { ref } from 'vue';
import hello from './components/hello.vue'

let teks = ref("")
</script>

<template>
  <input type="text" class="bg-slate-200" v-model=teks onfocus>
  <div class="text-3xl font-sans font-medium">
    <hello :content="teks" />
  </div>
</template>
