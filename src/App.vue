<template>
  <div id="app">
    <ToDoListHeader></ToDoListHeader>
    <ToDoList></ToDoList>
    <ToDoListFooter></ToDoListFooter>
  </div>
</template>

<script>
import ToDoList from './components/ToDoList.vue'
import ToDoListFooter from './components/ToDoListFooter.vue'
import ToDoListHeader from './components/ToDoListHeader.vue'


export default {
  name: 'App',
  components: {
    ToDoListFooter,
    ToDoList,
    ToDoListHeader
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
