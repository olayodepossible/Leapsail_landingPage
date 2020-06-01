<template>
  <div class="header">
    <div>
      <h1>CompanyLogo.</h1>
    </div>
    <nav class="navbar">
      <ul>
        <li>
          <img src="https://img.icons8.com/offices/30/000000/alarm.png" />
        </li>
        <li>
          <img src="https://img.icons8.com/color/30/000000/circled-dot.png" />
        </li>
        <li>
          <img src="https://img.icons8.com/offices/30/000000/gender-neutral-user.png" />
        </li>
        <li>
          <img src="https://img.icons8.com/offices/30/000000/menu-2.png" />
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {};
</script>
<style scoped>
.header {
  display: flex;
  position: fixed;
  width: 100%;
  z-index: 10;
  top: 0;
  background-color: #fff;
  font-size: 0.5rem;
}

.navbar {
  margin-left: auto;
}

.navbar li {
  display: inline-block;
  margin-right: 2rem;
  list-style: none;
}

.navbar li img {
  width: 20px;
}

.navbar li a {
  margin: 0;
  border: 0px;
}
</style>