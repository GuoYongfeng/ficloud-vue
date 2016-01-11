<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
<<<<<<< HEAD
      msg: '一起玩转Vue.js'
=======
      msg: 'Hello World!'
>>>>>>> 350ddc37bf43e0c05a30ae5c645a48e2b0063ea9
    }
  }
}
</script>
