<template>
  <div class="container">
    <Header />
    <hr />
    <div class="msg">
      <h1>Our pricing plan for everyone</h1>
      <p>Packages are for individual only</p>
    </div>
    <Container class="plans" />
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Layout/Header";
import Container from "../components/Container";
import Footer from "../components/Footer";
export default {
  name: "Homepage",
  components: {
    Header,
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
@import url("https://fonts.googleapis.com/css2?family=Catamaran:wght@900&display=swap");
hr {
  opacity: 0.1;
}
.container {
  width: 100%;
  height: 600px;
  margin: 0 auto;
  margin-top: 80px;
  background-image: url("../assets/snow_sakting.png");
  background-position: left 920px top -190px;
  background-repeat: no-repeat;
  background-size: 50%;
  font-family: Catamaran, Georgia, Times, "Times New Roman", "sans-serif";
}

/* .msg {
  margin-top: 120px;
} */
.msg h1 {
  line-height: 0.2rem;
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
