<template>
  <div id="bg">
    <div>
      
      <b-navbar toggleable="lg" type="dark" variant="Light">
        <b-avatar
          src="https://peakagro.co.th/wp-content/uploads/2017/10/home-logo-hi.png"
          size="2%"
        />
        <b-navbar-toggle target="nav-collapse"  />
        <b-collapse id="nav-collapse" is-nav>
          <br>
          <b-navbar-brand href="#">
            HOME
          </b-navbar-brand>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-navbar-nav>
              <b-nav-item id="aa" to="/">
                Home
              </b-nav-item>
              <b-nav-item id="aa" to="/Credit">
                Credit
              </b-nav-item>
            </b-navbar-nav>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <Nuxt />
    <br><br><br><br><br>
  </div>
</template>
<script>
export default {}
</script>
<style>
#bg {
  background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRpWc36v8M7GKuMaXutJTi-dkiFFuYfxnU7TKeMO5JGaMC7HWr_DyD4fh78236QKODveaMH9FxFMKz2Cw3gG8X0x0m2H0YXrP1_xw&usqp=CAU&ec=45707744);
  background-size: cover;
}
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: rgb(0, 0, 0);
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: rgb(0, 0, 0);
  background-color: #35495e;
}
#aa{
  color: black;
}
</style>
