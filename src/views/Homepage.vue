<template>
  <div class="container">
    <div class="msg">
      <h1>Our pricing plan for everyone</h1>
      <p>Packages are for individual only</p>
    </div>
    <Container />
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
@import url("https://fonts.googleapis.com/css2?family=Catamaran:wght@900&display=swap");
* {
  box-sizing: border-box;
}
.container {
  width: 100%;
  height: 600px;
  margin: 0 auto;
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
.msg p {
  font-family: Arial, Helvetica, sans-serif;
  color: rgb(224, 215, 215);
}
</style>
