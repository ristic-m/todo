<script>

import TodoList from './components/TodoList.vue'
import Counter from './components/Counter.vue'

export default {
  components: {
    TodoList,
    Counter
  },
  data() {
    return {
      todos: ['Clean room', 'Go to gym', 'Buy groceries']
    }
  }
}

</script>

<template>

  <div>
    <div>
      <h1>To-do list</h1>
      <TodoList :todos="todos" />
    </div>

    <div>
      <h1>Counter</h1>
      <Counter />

    </div>
  </div>
  


</template>

