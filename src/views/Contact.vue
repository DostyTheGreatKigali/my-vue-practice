<template>
  <div class="contact">
    <h1>This is a contact page</h1>
    <!-- <HelloWorld msg="Welcome to Contact Page"/> -->
    <Button title="Call" />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Button from '@/components/Button.vue'

export default {
  name: 'Contact',
  components: {
    // HelloWorld,
    Button
  }
}
</script>
