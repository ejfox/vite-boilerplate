<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" class="db center" />
    <HelloWorld />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
  },
}
</script>
