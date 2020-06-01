<template>
  <div class="footer">
    <div>companyLogo</div>
    <div class="terms">
      <ul>
        <li>Terms & Condition</li>
        <li>Career</li>
        <li>Privacy Policy</li>
        <li>Leapsail copyright 2020</li>
      </ul>
    </div>
    <div class="icon">
      <a href="#" target="_blank">
        <i class="fa fa-instagram fa-2x" aria-hidden="true"></i>
      </a>
      <a href="#" target="_blank">
        <i class="fa fa-twitter fa-2x" aria-hidden="true"></i>
      </a>
      <a href="#" target="_blank">
        <i class="fa fa-facebook fa-2x" aria-hidden="true"></i>
      </a>
      <a href="#" target="_blank">
        <i class="fa fa-linkedin fa-2x" aria-hidden="true"></i>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style  scoped>
@import "https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css";
.icon {
  margin-top: 1rem;
}
.icon a {
  padding: 0.5rem;
  color: #fff;
}
.icon a:hover {
  color: #eece1a;
  transition: all 0.5s ease-out;
}

.footer {
  display: flex;
  justify-content: space-between;
  padding: 20px 0px;
  background-color: #000;
  color: #fff;

  /* padding: 0 10px;
  background-color: #000;
  color: #fff;
  width: 100%;
  position: absolute;
  bottom: 20px;
  height: 60px; */
}

.terms ul {
  display: flex;
  list-style: none;
}

.terms li {
  border-right: 0.8px solid rgb(230, 215, 215);
  padding: 0.5rem;
}
</style>