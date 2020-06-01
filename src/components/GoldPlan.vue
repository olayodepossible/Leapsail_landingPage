<template>
  <div class="plan">
    <h1>GOLD</h1>
    <h3>&#8358; 2500</h3>
    <p>Per month</p>
    <button>Activated</button>
  </div>
</template>

<script>
export default {
  name: "GoldPlan",
  props: ["plans"]
};
</script>

<style scoped>
.gold h1 {
  color: #fff;
}
</style>