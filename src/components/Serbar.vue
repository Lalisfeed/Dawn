<template>
  <div class="bar">
    <div class="serb">
      <input type="text" placeholder="Iron Man">
      <input type="submit" value="Search">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Serbar',
  props: {
    hero: String
  }
}
</script>

<style scoped>
.bar {
  width: 100vw;
  height: auto;
  padding: 10px  20px 20px 20px;
  text-align: center;
}

.serb {
  max-width: 600px;
  height: 65px;
  display: flex;
  flex-direction: row;
  margin: auto;

}

input {
  font-size: 20px;
  margin: 10px 0px 4px 0px;
  padding: 5px 10px;
  border-radius: 0px;
  border-width: 0px;
  outline: none;
}

input:nth-of-type(1) {
  flex: 3;
  font-size: 22px;
  font-weight: 500;
  color: #ec1d24;
  background: #fefefe;
}

input:nth-of-type(2) {
  flex: 1;
  cursor: pointer;
  color: #fefefe;
  background: #ec1d24;
}

input:nth-of-type(2):hover {
  opacity: 0.9;
}

</style>