<template>
  <div id="app">
    <Header></Header>
    <Content></Content>
  </div>
</template>

<script>
import Header from './components/Header'
import Content from './components/Content'

export default {
  name: 'App',
  components: {
    Header,
    Content
  }
}
</script>

<style lang="scss">
@import "../node_modules/bulma/bulma.sass";
@import url('https://fonts.googleapis.com/css?family=Montserrat');

body {
  font-family: 'Montserrat' !important;
  overflow: hidden;
}
</style>

