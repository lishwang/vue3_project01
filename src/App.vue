<template>
  <div>
    <router-link to="/login">login</router-link>
    <router-link to="/main">main</router-link>

    <router-view></router-view>

    <h2>{{ $store.state.name }}</h2>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',

  components: {}
})
</script>

<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
