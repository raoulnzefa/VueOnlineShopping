<template>
  <ul class="todo-main">
    <ToDoListItem
      v-for="todoObj in todos"
      :key="todoObj.id"
      :todo="todoObj"
      :checkTodo="checkTodo"
      :deleteTodo="deleteTodo"
    />
  </ul>
</template>

<script>
import ToDoListItem from "./ToDoListItem.vue";
export default {
  name: "ToDoList",
  components:{
      ToDoListItem
  }
};
</script>

<style>
</style>