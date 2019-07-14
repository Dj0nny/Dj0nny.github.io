<template>
  <div id="app">
      <Header></Header>
    <b-container>
      <Content></Content>
    </b-container>
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
}

a {
    color: #000;
}

a:hover {
    color: #000;
    text-decoration: underline;
}
</style>

