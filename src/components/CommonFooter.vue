<template>
  <footer class="top-footer">
        <div class="footer-bar">

            <h1 class="footer-logo">estra inc.</h1>
            <nav class="footer-nav">
              <ul>
                <li><a href="#">home</a></li>
                <li><a href="#">about</a></li>
                <li><a href="#">service</a></li>
                <li><a href="#">works</a></li>
                <li><a href="#">price</a></li>
                <li><a href="#">contact</a></li>
              </ul>
            </nav>
          
          
        </div>
        <small>Copyright 2019 estra inc. All Rights Reserved.</small>
  </footer>
</template>

<style scoped>



.top-footer {
  height: 70px;
  background: #000;
}

.footer-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.footer-logo {
  font-size: 20px;
  font-weight: bold;
  margin-left: 35px;
  color: #f2f2f2;
  line-height: 70px;
}

.footer-nav ul {
  display: flex;
}

.footer-nav li {
  margin-right: 35px;
  font-size: 16px;
}

.footer-nav a {
  color: #f2f2f2;
  text-decoration: none;
}

.top-footer small {
  text-align: center;
}
</style>