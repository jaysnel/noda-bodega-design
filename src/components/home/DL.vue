<template>
  <div class="dl">
      <h1>NoDa Bodega</h1>
  </div>
</template>

<script>
export default {
    name: "DL"
}
</script>

<style scoped>
    .dl {
        display: flex;
        justify-content: center;
        align-items: center;

        background: url("../../assets/images/dl.jpg");
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;

        height: 100vh;
    }

    .dl h1 {
        color: #fff;
    }
</style>