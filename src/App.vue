<template>
  <div id="app">
    <Nav class="mb-6" />
    <HelloWorld msg="Welcome to Your Vue.js App" class="text-center"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Nav from './components/Nav.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Nav
  }
}
</script>