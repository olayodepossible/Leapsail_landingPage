<template>
  <div class="plan">
    <div>
      <h1>BRONZE</h1>
      <h3>&#8358; 500</h3>
      <p>Per month</p>
      <button>Activated</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "BronzePlan",
  props: ["plans"]
};
</script>

<style scoped>
.bronze h1 {
  color: green;
}
</style>