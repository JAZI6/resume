<template>
  <div id="app">
    <mainContent></mainContent>
  </div>
</template>

<script>
import mainContent from './components/mainContent'

export default {
  components: {
    'mainContent': mainContent
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
ul,ol,li{
  list-style: none;
}
a{
  text-decoration: none;
  color: #333;
}
</style>

