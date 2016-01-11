<template>
  <div id="app">
    <hello></hello>
    <two-way-bind></two-way-bind>
    <todo></todo>
  </div>
</template>

<script>
import Hello from './components/Hello'
import Todo from './components/Todo'
import TwoWayBind from './components/TwoWayBind.vue'

export default {
  components: {
    'hello': Hello,
    'two-way-bind': TwoWayBind,
    'todo': Todo
  }
}

</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
