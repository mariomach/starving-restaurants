<template>
<section class="hero is-info is-large">
  <div class="hero-head">
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <!-- <a class="navbar-item">
            <img src="https://bulma.io/images/bulma-type-white.png" alt="Logo">
          </a> -->
          <p class="title"> Starving Restaurants</p>
          <span class="navbar-burger burger" data-target="navbarMenuHeroB">
            <span></span>
            <span></span>
            <span></span>
          </span>
        </div>
        <div id="navbarMenuHeroB" class="navbar-menu">
          <div class="navbar-end">
            <a class="navbar-item is-active">
              <NLink to="/" class="navbar-font">Home</NLink>
              
            </a>
            <a class="navbar-item is-active">
              <nuxt-link to="/fans" class="navbar-font">Fans</nuxt-link>
            </a>
            <a class="navbar-item is-active">
              <nuxt-link to="/restaurants" class="navbar-font">Restaurants</nuxt-link>
            </a>
            <a class="navbar-item is-active">
              <nuxt-link to="/faq" class="navbar-font">FAQ</nuxt-link>
            </a>

              <a class="navbar-item is-active">
              <nuxt-link to="/contact" class="navbar-font">Contact</nuxt-link>
            </a>
           
          </div>
        </div>
      </div>
    </nav>
  
   
<!--  <a class="navbar-item">
      <nuxt-link to="/fans">
        Fans
      </nuxt-link>
    </a> -->

</div>
</section>



</template>

<style scoped>
.brand {
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  font-size: 1.5em;
  color: #39b982;
  text-decoration: none;
}

.end {
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  font-size: 1.3em;
  color: #39b982;
  text-decoration: none;
}

link {
    color: #0060B6;
    text-decoration: none;
}

a:hover 
{
     color:#00A0C6; 
     text-decoration:none; 
     cursor:pointer;  
}

.navbar-font
{
  text-decoration: none;
  color:aliceblue;
}

.title
{
  padding-top: 15px;
  /* margin-top: 10px; */
}

.is-active{
  background-color: blue;
}
</style>

