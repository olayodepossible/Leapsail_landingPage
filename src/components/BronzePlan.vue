<template>
  <div class="bronze">
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
.bronze {
  text-align: center;
  font-family: Catamaran, Georgia, Times, "Times New Roman", "sans-serif";
}
.bronze h1 {
  color: green;
}
.bronze h3 {
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