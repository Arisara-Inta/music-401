<template>
  <div id="bg">
    <div>
      
      <b-navbar toggleable="lg" type="dark" variant="Light">
        <b-avatar
          src="https://www.samba.com.pk/samba/themes/samba/assets/images/home_icon.png"
          size="1.5%"
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
  background-image: url(https://crosstheology.files.wordpress.com/2015/05/fotolia_45452813_subscription_monthly_l.jpg);
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
  border: 1px solid white;
  color: white;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: rgb(0, 0, 0);
  background-color: white;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid white;
  color: white;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: rgb(0, 0, 0);
  background-color: white;
}
#aa{
  color: black;
}
</style>
