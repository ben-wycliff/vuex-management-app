<template>
  <div id="app">
    <div class="container">
      <AddTodo />
      <TodoFilter />
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos'
import AddTodo from './components/AddTodo'
import TodoFilter from './components/TodoFilter'
export default {
  name: 'App',
  components: {
    Todos,
    AddTodo,
    TodoFilter
  }
}
</script>

<style>
*{
  font-family: 'Quicksand', fantasy ;
}
body {
  line-height: 1.6;
  background: #e8f7f0;
}
.container{
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
