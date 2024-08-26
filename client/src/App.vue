<template>
  <div id="app">
    <AddList />

    <TodoList />
  </div>
</template>

<script>
import TodoList from "./components/TodoList.vue";
import AddList from "./components/AddList.vue";

export default {
  name: "App",
  components: {
    TodoList,
    AddList,
  },
};
</script>

<style>
@import "./index.css";
</style>
