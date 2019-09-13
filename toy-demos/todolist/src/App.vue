<template>
  <div id="app">
    <Todos />
  </div>
</template>

<script>
import Todos from './components/Todos';
export default {
  name: 'app',

  components: {
    Todos,
  },
  data() {
    return {
      todos: [
        {
          id: 1,
          title: "待办事项1",
          completed: true,
        },
        {
          id: 2,
          title: "待办事项2",
          completed: true,
        },
        {
          id: 3,
          title: "待办事项3",
          completed: true,
        }
      ]
    }
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}
</style>
