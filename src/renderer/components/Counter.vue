<template>
  <div id="counter">
    <div>{{count}}</div>
    <button @click="countUp">plus</button>
    <button @click="countDown">minus</button>
  </div>
</template>

<script>
export default {
  name: 'counter',
  data () {
    return {
      count: 0
    }
  },
  methods: {
    countUp () {
      this.count++
    },
    countDown () {
      this.count--
    }
  }
}
</script>

<style>
  /* CSS */
</style>
