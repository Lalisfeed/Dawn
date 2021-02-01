<template>
  <div class="noload">
    <h1>Fury Is Busy...</h1>
  </div>
</template>

<script>
export default {
  name: 'Noload',
  props: {
    noloader: String
  }
}
</script>

<style scoped>

.noload {
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    align-content: center;
    height: auto;
    opacity: 0.7;
}

</style>