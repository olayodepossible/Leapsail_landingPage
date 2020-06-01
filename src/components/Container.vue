<template>
  <div class="plan-container">
    <div class="plan-feature">
      <div>
        <h3>Plan features</h3>
      </div>
      <BronzePlan class="bronze" />
      <SilverPlan class="silver" />
      <GoldPlan class="gold" />
    </div>
    <div class="list"></div>
  </div>
</template>

<script>
import BronzePlan from "./BronzePlan";
import SilverPlan from "./SilverPlan";
import GoldPlan from "./GoldPlan";

export default {
  name: "Container",
  components: {
    BronzePlan,
    SilverPlan,
    GoldPlan
  }
};
</script>

<style scoped>
.plan-container {
  background-color: #fff;
  box-shadow: #fff;
  z-index: 2;
}
.plan-feature {
  display: flex;
  justify-content: space-between;
}
</style>