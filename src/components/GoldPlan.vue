<template>
  <div class="gold">
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
.gold {
  text-align: center;
  font-family: Catamaran, Georgia, Times, "Times New Roman", "sans-serif";
}
.gold h1 {
  color: blueviolet;
}
.gold h3 {
  font-size: 2rem;
}

button {
  width: 150px;
  border: 0;
  padding: 7px;
  margin: 20px;
  border-radius: 15px;
  background-color: orangered;
  color: #fff;
}
</style>