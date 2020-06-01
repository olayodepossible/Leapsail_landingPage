<template>
  <div class="plan">
    <h1>SILVER</h1>
    <h3>&#8358; 2000</h3>
    <p>Per month</p>
    <button>Activated</button>
  </div>
</template>

<script>
export default {
  name: "SilverPlan",
  props: {
    plan: String,
    cost: String
  }
};
</script>

<style scoped>
.silver h1 {
  color: blueviolet;
}
</style>