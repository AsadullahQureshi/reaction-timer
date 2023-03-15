<template>
  <h1>Welcome in Reaction Timer </h1>
    <BlockBlock />
</template>

<script>
import BlockBlock  from './components/Block.vue'
export default {
  name: 'app',
  components: {BlockBlock}

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #444;
  margin-top: 60px;
}
</style>
