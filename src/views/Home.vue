<template>
  <div id="home">
    <h1>This is an home page</h1>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  props: {
    msg: String
  },
  components: {
    // HelloWorld
  }
}
</script>
