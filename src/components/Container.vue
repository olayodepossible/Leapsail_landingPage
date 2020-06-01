<template>
  <div class="container-plan">
    <div class="plan-feature">
      <div class="plan">
        <h3>Plan features</h3>
      </div>
      <BronzePlan class="bronze" />
      <SilverPlan class="silver" />
      <GoldPlan class="gold" />
    </div>
    <Features />
  </div>
</template>

<script>
import BronzePlan from "./BronzePlan";
import SilverPlan from "./SilverPlan";
import GoldPlan from "./GoldPlan";
import Features from "./Features";

export default {
  name: "Container",
  components: {
    BronzePlan,
    SilverPlan,
    GoldPlan,
    Features
  }
};
</script>

<style scoped>
.container-plan {
  background-color: #fff;
  color: rgba(0, 0, 0, 0.39);
}
.plan-feature {
  display: flex;
}
.plan {
  margin-left: 20px;
  margin-top: 80px;
  font-size: 2rem;
}
</style>