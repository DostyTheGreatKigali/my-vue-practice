<template>
  <div class="button">
    <button>{{ title }}</button>
  </div>
</template>

<script>
export default {
  name: 'Button',
  props: {
    title: String,
    // color: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
button {
  padding: 0.5em;
  width: 10em
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

