<template>
    <div id="app">
      <Header/>
      <SideLayout/>
    </div>
</template>

<script>
  import SideLayout from './components/Layouts/SideLayout';
  import Header from './components/Layouts/Header';

export default {
  name: 'app',
  components: {
      SideLayout,
      Header
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
