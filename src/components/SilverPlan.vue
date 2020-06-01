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
  name: "SilverPlan"
};
</script>

<style scoped>
.silver {
  position: relative;
  top: -20px;
  background-color: rgba(0, 140, 255, 0.959);
  border-radius: 15px;
  text-align: center;
  font-family: Catamaran, Georgia, "sans-serif";
}
.silver h1 {
  color: #fff;
}
.silver h3 {
  font-size: 2rem;
}

button {
  width: 120px;
  border: 0;
  padding: 7px;
  margin: 40px;
  margin-bottom: 50px;
  border-radius: 15px;
  background-color: #fff;
  color: orangered;
}
</style>