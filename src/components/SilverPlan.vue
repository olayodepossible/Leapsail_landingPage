<template>
  <div class="silver">
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
.silver {
  background-color: rgba(0, 140, 255, 0.959);
  border-radius: 5px;
  text-align: center;
  font-family: Catamaran, Georgia, "sans-serif";
}
.silver h1 {
  color: #fff;
}

button {
  width: 150px;
  border: 0;
  padding: 7px;
  margin: 20px;
  border-radius: 15px;
  background-color: #fff;
  color: orangered;
}
</style>