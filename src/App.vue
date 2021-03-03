<template>
  <div id="app">
    <h1>Hello 首頁</h1>
  </div>
</template>

<script>

export default {
  name: 'App',
  data: () => ({
    //
  }),
  mounted() {
    console.log('Page Mounted');
  },
  sockets: {
    connect() {
      console.log('server connected');
    },
  },
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
}
</style>
