<template>
  <ul class="todo-main">
    <MyItem
      v-for="todoObj in todos"
      :key="todoObj.id"
      :todo="todoObj"
      :checkTodo="checkTodo"
      :deleteTodo="deleteTodo"
    />
  </ul>
</template>

<script>
import ToDoListItem from "./components/ToDoListItem.vue";
export default {
  name: "ToDoList",
};
</script>

<style>
</style>