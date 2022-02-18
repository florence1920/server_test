<template>
  <div class="home">
    <button @click="foo">submit</button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  methods: {
    foo() {
      this.$http.get('/users')
    }
  },
}
</script>
