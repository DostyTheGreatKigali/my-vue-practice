<template>
  <div class="about">
    <h1>This is an about page</h1>
      <Button title="Read more" />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Button from '@/components/Button.vue'

export default {
  name: 'About',
  components: {
    // HelloWorld,
    Button
  }
}
</script>