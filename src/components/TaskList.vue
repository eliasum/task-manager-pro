<script setup lang="ts">
// В будущем задачи будут приходить сюда через props
const tasks = [
  { id: 1, text: 'Изучить основы Vue', completed: true },
  { id: 2, text: 'Создать первые компоненты', completed: false },
]
</script>

<template>
  <ul>
    <li v-for="task in tasks" :key="task.id">
      {{ task.text }}
    </li>
  </ul>
</template>
