<template>
  <div id="about">
    <h1>This is an about page</h1>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'About',
  props: {
    msg: String
  },
  components: {
    // HelloWorld
  }
}
</script>
