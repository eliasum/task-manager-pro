<script setup lang="ts">
import { ref } from 'vue'

const newTaskText = ref('')
</script>

<template>
  <div>
    <input v-model="newTaskText" placeholder="Что нужно сделать?" type="text" />
    <button>Добавить</button>
  </div>
</template>
