<template>
  <div class="mainContent">
    <leftPanel></leftPanel>
    <rightPanel></rightPanel>
  </div>
</template>

<script>
import leftPanel from './leftPanel'
import rightPanel from './rightPanel'

export default {
  components: {
    'leftPanel': leftPanel,
    'rightPanel': rightPanel
  }
}
</script>

<style lang="scss">
.mainContent{
  font-family: "Avenir","Open Sans","Helvetica Neue",Helvetica,Arial,sans-serif;
  color: #333;
  font-size: 16px;
  width: 1100px;
  margin: 30px auto;
  padding: 0 30px;
  padding-bottom: 30px;
  background-color: #dfdfdf;
  border-radius: 20px;
  display: flex;
  justify-content: space-between;
}
</style>

