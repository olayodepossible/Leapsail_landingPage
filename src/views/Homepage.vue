<template>
  <div class="container">
    <div class="msg">
      <h1>Our pricing plan for everyone</h1>
      <p>Packages are for individual only</p>
    </div>
    <Container class="plans" />
    <Footer />
  </div>
</template>

<script>
import Container from "../components/Container";
import Footer from "../components/Footer";
export default {
  name: "Homepage",
  components: {
    Container,
    Footer
  },
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  width: 100%;
  height: 600px;
  margin: 0 auto;
  margin-top: 80px;
  background-image: url("../assets/snow_sakting.png");
  background-position: left 420px top -190px;
  background-repeat: no-repeat;
  background-size: 80%;
}

/* .msg {
  margin-top: 120px;
} */
.msg h1 {
  line-height: 0.2rem;
  font-family: Catamaran, Georgia, Times, "Times New Roman", "sans-serif";
}

.plans {
  width: 50%;
  margin: 0 auto;
  margin-top: 120px;
  margin-bottom: 120px;
  border-radius: 10px;
  border: 2px solid green;
}
</style>
