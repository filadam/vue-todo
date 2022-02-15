<template>
  <todo-list list-name="Lista do zrobienia..." />
</template>

<script>
import TodoList from "./components/TodoList.vue";
export default {
  name: "App",
  components: {
    TodoList,
  },
};
</script>
