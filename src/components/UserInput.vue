<template>
  <form @submit.prevent="logInput">
    <input type="text" v-model="input.text" />
    <button type="submit">Enter</button>
  </form>
</template>
</template>

<script>
export default {
  data () {
    return {
      input: {
        text: ''
      }
    }
  },
  methods: {
    logInput () {
      console.log(this.input.text)
    }
  }
}
</script>

<style>
form {
  padding: 10px;
  margin: 0;
  display: flex;
  border-bottom: 1px solid white;
}
input {
  flex-grow: 1;
  background: black;
  padding: 10px;
  font-size: 1rem;
  border: none;
  color: white;
}
button {
  background: white;
  margin-left: 10px;
}
</style>
