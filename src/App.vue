 <template>
  <div id="app">
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
    <hr />
    <router-view />
  </div>
</template>


<style>
@import url("https://fonts.googleapis.com/css2?family=Catamaran:wght@900&display=swap");

hr {
  opacity: 0.1;
}

p {
  font-family: Arial, Helvetica, sans-serif;
  color: rgb(224, 215, 215);
}
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
