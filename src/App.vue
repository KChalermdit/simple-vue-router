<template>
  <div class="bg-yellow-100 font-semibold">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <div id="contents" class="bg-blue-100">
    <router-view msg="Hello World" />
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {}
  },
  methods: {}
}
</script>
