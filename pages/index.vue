<template>
  <div>
    counter: {{ counter }}
    <button @click="plus">
      plus
    </button>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data () {
    return {
      counter: 0
    }
  },
  methods: {
    plus () {
      this.counter++
    }
  }
})
</script>
