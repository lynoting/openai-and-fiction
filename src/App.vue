<template>
  <div>
    <AskGPT />
  </div>
 </template>
<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import AskGPT from './components/AskGPT.vue';

@Options({
  components: {
    AskGPT
    },
})
export default class App extends Vue {}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
html, body{
  background-color:#F29089;
}

</style>
