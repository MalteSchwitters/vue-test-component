<template>
  <button @click="increase">
    <span>This Button has been clicked {{ current }} times</span>
  </button>
</template>

<script>
  export default {
    props: {
      start: Number 
    },

    data() {
      return {
        current: this.start,
      }
    },

    methods: {
      increase() {
        this.current++;
      }
    }
  }
</script>
