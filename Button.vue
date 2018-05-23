<template>
  <button @click="click">{{ title }}</button>
</template>

<script>
export default {
  data () {
    return {
      title: 'Click',
      message: 'Hello!'
    }
  },

  methods: {
    click () {
      alert(this.message)
    }
  }
}
</script>

<style>
button {
  color: tomato;
  height: 40px;
}
</style>


