<template>
  <div class="container">
    <div class="plan-feature">
      <div>
        <h3>Plan features</h3>
      </div>
      <BronzePlan class="bronze" />
      <GoldPlan class="gold" />
      <SilverPlan class="silver" />
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
.plan-feature {
  display: flex;
  justify-content: space-between;
  color: red;
}
</style>