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
  },
    data() {

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
    body{
        background: #2980B9;  /* fallback for old browsers */
        background: -webkit-linear-gradient(to bottom, #FFFFFF, #6DD5FA, #2980B9);  /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to bottom, #FFFFFF, #6DD5FA, #2980B9); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
        background-repeat: no-repeat;
        background-attachment: fixed;
    }
</style>
