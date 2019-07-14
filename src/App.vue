<template>
  <div id="app">
    <div class="container">
      <Header></Header>
      <Content></Content>
    </div>
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
@import url('https://fonts.googleapis.com/css?family=Montserrat');

body {
  font-family: 'Montserrat' !important;
  overflow: hidden;
}
</style>

