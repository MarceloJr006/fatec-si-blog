<template>
  <div class="container">
    <div class="cabeca">
      <h1>Texto1</h1>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
  .container{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(10, 1fr);
  }
  .cabeca{
    display: flex;
    grid-column: 2/3;
    grid-row: 1/1;
  }
</style>