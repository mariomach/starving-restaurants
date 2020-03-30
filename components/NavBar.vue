<template>
<section class="hero is-info is-large">
  <div class="hero-head">
    <div class="container">
      <div class="nav">
        <nuxt-link to="/" class="brand">
          Hungry Restaurants
        </nuxt-link>
        <nav>
          <nuxt-link to="/" class="end">
            <h5 class="has-text-white">Home</h5>
          </nuxt-link> |
          <nuxt-link to="/fans" class="end">
            <h5 class="has-text-white">Seattle</h5>
          </nuxt-link> |
            <nuxt-link to="/restaurants" class="end">
            <h5 class="has-text-white">Restaurants</h5>
          </nuxt-link> |
            <nuxt-link to="/challenges" class="end">
            <h5 class="has-text-white">Challenges</h5>
          </nuxt-link> |
              <nuxt-link to="/faq" class="end">
            <h5 class="has-text-white">FAQ</h5>
              </nuxt-link> |
              <a href="https://docs.google.com/forms/d/e/1FAIpQLSfKO87747DSyvaEJDxP-kInT5kqA3SB6skZErquEfMTnEZNsg/viewform">
            <h5 class="has-text-white">Sign Up</h5>
              </a>

        </nav>
      </div>
    </div>
  </div>
</section>
</template>

<style scoped>
.brand {
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  font-size: 1.2em;
  /* color: #cc6600; */
  color: aliceblue;
  text-decoration: none;
  margin-left: 12px;
  margin-top: 0px;
}
.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 60px;
}
.nav .nav-item {
  box-sizing: border-box;
  margin: 0 5px;
  color: rgba(0, 0, 0, 0.5);
  text-decoration: none;
}
.nav .nav-item.router-link-exact-active {
  color: #39b982;
  border-bottom: solid 2px #39b982;
}
.nav a {
  display: inline-block;
}

/* .brand
{
  color:aliceblue;
  text-decoration: none;
} */
</style>