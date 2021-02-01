<template>
  <div class="web">
    <h1>Marvel</h1>
    <br>
    <h4>> Is your Hero here?</h4>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.web {
  width: 100vw;
  height: auto;
  padding: 10px 0px;
  margin-bottom: 10px;
  color: #fff;
}

h1 {
  font-size: 52px;
  color: #fefefe;
  margin: 10px 0px 0px 0px;
}

</style>