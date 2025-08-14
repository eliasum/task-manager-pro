<script setup lang="ts">
import TaskInput from './components/TaskInput.vue'
import TaskList from './components/TaskList.vue'
</script>

<template>
  <main style="padding: 20px; font-family: sans-serif">
    <h1 style="font-size: 2em; margin-bottom: 1em">Task Manager Pro</h1>
    <TaskInput />
    <TaskList />
  </main>
</template>
