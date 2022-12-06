<template>
  <div id="app">
    <SongChoice/>
    <PlayList/>

  </div>
</template>

<script>
import SongChoice from '@/components/SongChoice.vue';
import PlayList from '@/components/PlayList.vue';

export default {
  name: 'App',
  components: {
    SongChoice,
    PlayList

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: bisque;
}
</style>
