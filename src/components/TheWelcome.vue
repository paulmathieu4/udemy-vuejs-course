<script lang="ts">
export default {
  data() {
    return {
      counter: 0
    }
  },
  methods: {
    incrementCounter() {
      this.counter++
    },
    decrementCounter() {
      this.counter--
    }
  }
}
</script>

<template>
  <h2>Events in Action</h2>
  <button v-on:click="counter++">Add</button>
  <button v-on:click="counter--">Remove</button>
  <p>Result: {{ counter }}</p>
</template>
