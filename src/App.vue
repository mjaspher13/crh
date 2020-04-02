<template>
  <div id="app">
    <header class="navbar">
      <div class="container">
        <div class="navbar-content">
          <span class="navbar-logo">CRH SAMPLE</span>
          <ul class="navbar-link-list">
            <li class="navbar-link">
              <a href="/news">NEWS</a>
            </li>
            <li class="navbar-link">
              <a href="/services">SERVICES</a>
            </li>
            <li class="navbar-link">
              <a href="/company">COMPANY</a>
            </li>
            <li class="navbar-link">
              <a href="/contact">CONTACT</a>
            </li>
          </ul>
        </div>
      </div>
    </header>
    <div class="container">
      <div class="main-content">
        <div class="image-container">
          <img class="image" alt="keyvisual" src="./assets/keyvisual.png" />
        </div>
        <h1>SAMPLE 1</h1>
        <div
          class="article"
        >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>
        <h1>NEWS</h1>
        <div>
          <span>2013/05/01</span>
        </div>
      </div>
    </div>
    <footer class="footer">Copyrigth (C) 2013 CHRSAMPLE All Rights reserved</footer>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
html,
body,
div,
span {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
#app {
  color: #333333;
}
.container {
  position: relative;
  margin: 0 160px;
}
.main-content {
  padding: 100px 0 0;
}
.image-container {
  margin-top: 30px;
}
.image-container > .image {
  display: block;
  height: 100%;
  width: 100%;
}

.navbar {
  position: fixed;
  z-index: 9;
  top: 0;
  width: 100%;
  background-color: #78c6e8;
  color: white;
}

.navbar-content {
  display: inline-flex;
  flex-direction: column;
  height: 100px;
  width: 100%;
  justify-content: center;
  align-items: center;
}

.navbar-logo {
  font-size: 36px;
  position: absolute;
  left: 0;
}
.navbar-link-list {
  align-self: flex-end;
  list-style-type: none;
  margin: 0;
  padding: 0;
  font-size: 16px;
}

.navbar-link:last-child {
  margin-right: 0;
}
.navbar-link {
  float: left;
  margin: 0 1em;
  text-decoration: none;
}
.navbar-link > a {
  color: white;
  text-decoration: none;
}
.article {
}
.footer {
  display: flex;
  justify-content: center;
  align-items: center;
  position: fixed;
  height: 58px;
  font-size: 12px;
  text-align: center;
  z-index: 9;
  bottom: 0;
  width: 100%;
  background-color: #78c6e8;
  color: white;
}
</style>
