<script setup lang="ts">
import { ref } from 'vue'

// В будущем задачи будут приходить сюда через props
const tasks = ref([
  { id: 1, text: 'Изучить методы массивов JS', completed: true },
  { id: 2, text: 'Применить v-for в Vue', completed: false },
  { id: 3, text: 'Выпить чаю', completed: false },
])
</script>

<template>
  <ul>
    <li v-for="task in tasks" :key="task.id">
      <input type="checkbox" :checked="task.completed" />
      <span>{{ task.text }}</span>
    </li>
  </ul>
</template>
