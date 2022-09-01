<template>
  <div id="app">
    <AppHeader />
  </div>
</template>

<script>
import AppHeader from "@/components/AppHeader";

export default {
  name: 'App',
  components: {
    AppHeader
  }
}
</script>

<style>
@import "assets/static/scss/main.scss";
</style>
