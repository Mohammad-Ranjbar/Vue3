<template>
  <div style="display: flex; justify-content: space-around">
  <div>
    <TodosList />
  </div>

  <div>
    <TodoListV3 title="Composition API" />
  </div>
</div>
</template>

<script>
import TodosList from "./components/TodosList";
import TodoListV3 from "./components/TodoListV3"
export default {
  name: 'App',
  components: {
      TodosList,
         TodoListV3,
  }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
