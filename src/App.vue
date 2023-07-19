<template>
  <div id="app">
    <Header />
    <Breadcrumbs />
    <Main />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Breadcrumbs from './components/Breadcrumbs.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Header,
    Breadcrumbs,
    Main
  }
}
</script>

<style lang="scss"></style>
