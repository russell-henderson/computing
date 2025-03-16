// TaskCard.vue - Represents an individual task
<template>
  <div class="task-card" :class="{ completed: task.completed }">
    <input type="checkbox" v-model="task.completed" @change="$emit('update-task', task)" />
    <span>{{ task.title }}</span>
    <button @click="$emit('edit-task', task)">✏️</button>
    <button @click="$emit('delete-task', task.id)">🗑️</button>
  </div>
</template>

<script>
export default {
  props: ['task'],
  emits: ['update-task', 'edit-task', 'delete-task']
};
</script>

<style scoped>
.task-card {
  display: flex;
  align-items: center;
  background: var(--card-bg);
  padding: 10px;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  margin-bottom: 10px;
}
.completed span {
  text-decoration: line-through;
}
</style>
