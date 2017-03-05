<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
*,
*::before,
*::after {
  box-sizing: border-box;
}
html, body {
  margin: 0;
  padding: 0;
  font-size: 100%;
  font-family: 'Roboto', sans-serif;
}
</style>
