<template>
  <div class="plan">
    <h1>{{plan}}</h1>
    <h3>{{cost}}</h3>
    <p>Per month</p>
    <button>Activated</button>
  </div>
</template>

<script>
export default {
  name: "Plan",
  props: {
    plan: String,
    cost: String
  }
};
</script>

<style scoped>
</style>