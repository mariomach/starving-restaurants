<template>
<div>
  <section class="hero is-info is-fullheight-with-navbar">
  <div class="hero-body">
    <div class="container has-text-centered">
      <div class="container has-text-centered">
      <h1 class="title is-size-2">
        <!-- <strong>To Bail Out Or Not</strong> -->
        <strong>Your local favourite restaurants are going hungry ...</strong>
      </h1>
      <h2 class="subtitle is-size-4">
        And they might not be able to take care of you again :(
         <i class="fas fa-sad-tear"></i>
      </h2>
       <div class="container">
      <div class="button is-danger"><p class="is-size-5">Learn more </p></div>
      </div>
      <div class="container">
      <!-- <h1 class="title">Dominos</h1> -->
      </div>
      </div>

     
    </div>
  </div>
</section>

 <section class="section">
  <div class="container is-fluid has-text-centered">
    <h6 class="subtitle has-text-grey"> In response to initiatives from</h6>
    <!-- <h1 class="title">MSFT WHO</h1> -->
    <!-- <div class="container"></div> -->
    <div class="container has-text-centered">
      <div class="level">
        <div class="level-item"><figure class="image is-128x128">
      <img src="~/static/slow.png">
    </figure></div>
    <div class="level-item"><figure class="image is-128x128">
      <img src="~/static/who.png">
    </figure></div>
       <div class="level-item"> <figure class="image is-128x128">
      <img src="~/static/dev.jpg">
    </figure></div>
        <div class="level-item"><figure class="image is-128x128">
      <img src="~/static/msft.png">
    </figure></div>
    </div>
    </div>
  </div>
</section>


  <section class="section has-background-link">
  <div class="container is-fluid  ">

 <div class="level">
  <div class="level-left">
    <div class="column">
    <p class="title has-text-white"> Time is short </p>
    <div class="container">
      </div>
    <p class="subtitle has-text-white">
      Revenues are falling. Costs are fixed. 
      Will the restaurants make it out? 
      </p>
    <p class="subtitle has-text-white">
      Your guess is as good as mine. But wait...
    </p>
    <p class="subtitle has-text-weight-bold has-text-white">
    What if there is a way you can help them and in return get rewarded?
    </p>
        <!-- <p class="subtitle has-text-white">
    Interested in finding out how?
    </p> -->
    <div class="button is-danger"><p class="is-size-5">Find out </p></div>
    <div class="button is-warning"><p class="is-size-5">Restaurants </p></div>
      <div class="container"></div>
    </div>
    </div>
  <div class="level-item">
        <p class="subtitle"> Video To Be Released.
      </p>
  </div>
</div>
  </div>
</section>

<section class="section">
    <div class="container is-fluid">
      <p class="title"> Seattle's Favourites</p>
  <div class="tile is-ancestor">
  <div class="tile is-vertical is-8">
    <div class="tile">
      <!-- Left Column -->
      <div class="tile is-parent is-vertical">
        <article class="tile is-child notification is-danger">
          <div class="level">
          <div class="level-left">
            <p class="title">Kedai Makan</p>
            </div>
          <div class="level-right">
          <button class="button is-success"><nuxt-link to="/fans" class="navbar-font"><strong>Support them</strong></nuxt-link></button> 
          </div>
          </div>
          <figure class="image is-4by3">
             <img src="~/static/kedai.jpg">
          </figure>
        </article>

   <article class="tile is-child notification is-danger">
          <div class="level">
          <div class="level-left">
            <p class="title">Lola</p>
            </div>
          <div class="level-right">
          <button class="button is-success"><nuxt-link to="/fans" class="navbar-font"><strong>Support them</strong></nuxt-link></button> 
          </div>
          </div>
          <figure class="image is-4by3">
            <img src="~/static/lola.jpg">
          </figure>
        </article>
      </div>
      <!-- Middle Column  -->
      <div class="tile is-parent is-vertical">
        <article class="tile is-child notification is-danger">
          <div class="level">
          <div class="level-left">
            <p class="title">Sushi Kashiba</p>
            </div>
          <div class="level-right">
          <button class="button is-success"><nuxt-link to="/fans" class="navbar-font"><strong>Support them</strong></nuxt-link></button> 
          </div>
          </div>
          <figure class="image is-4by3">
             <img src="~/static/kashiba.jpg">
          </figure>
        </article>

        <article class="tile is-child notification is-danger">
          <div class="level">
          <div class="level-left">
            <p class="title">Musashi</p>
            </div>
          <div class="level-right">
          <button class="button is-success"><nuxt-link to="/fans" class="navbar-font"><strong>Support them</strong></nuxt-link></button> 
          </div>
          </div>
          <figure class="image is-4by3">
             <img src="~/static/musashi.jpg">
          </figure>
        </article>
      </div>
    </div>
    <!-- <div class="tile is-parent">
      <article class="tile is-child notification is-danger">
        <p class="title">Wide tile</p>
        <p class="subtitle">Aligned with the right tile</p>
        <div class="content">
          <!-- Content -->
        <!-- </div>
      </article>
    </div> -->
  </div>
  <!-- Right Column -->
 <div class="tile is-parent is-vertical"> 
   <article class="tile is-child notification is-danger">
          <div class="level">
          <div class="level-left">
            <p class="title">Oddfellows</p>
            </div>
          <div class="level-right">
          <button class="button is-success"><nuxt-link to="/fans" class="navbar-font"><strong>Support them</strong></nuxt-link></button> 
          </div>
          </div>
          <figure class="image is-4by3">
             <img src="~/static/oddfellows.jpg">
          </figure>
        </article>

           <article class="tile is-child notification is-danger">
          <div class="level">
          <div class="level-left">
            <p class="title">Peony</p>
            </div>
          <div class="level-right">
          <button class="button is-success"><nuxt-link to="/fans" class="navbar-font"><strong>Support them</strong></nuxt-link></button> 
          </div>
          </div>
          <figure class="image is-4by3">
            <img src="~/static/peony.jpg">
          </figure>
        </article>
  </div>

  <nuxt-link to="/fans" class="navbar-font"></nuxt-link>
</div>

    </div>
</section>


<!-- <div class="column">
<div class="tile is-ancestor">
  
  <div class="tile is-parent">
    <article class="tile is-child box">
      <p class="title">Hello World</p>
      <Table></Table>
      <p class="subtitle">What is up?</p>
    </article>
  </div>

  <!-- <div class="tile is-parent">
    <article class="tile is-child box">
      <p class="title">Foo</p>
      <p class="subtitle">Bar</p>
    </article>
  </div>
  <div class="tile is-parent">
    <article class="tile is-child box">
      <p class="title">Third column</p>
      <p class="subtitle">With some content</p>
      <div class="content">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ornare magna eros, eu pellentesque tortor vestibulum ut. Maecenas non massa sem. Etiam finibus odio quis feugiat facilisis.</p>
      </div>
    </article>
  </div> -->
<!-- </div> -->
</div>
</div>




</template>

<script>
import Logo from '~/components/Logo.vue'
import Table from '~/components/Table.vue'

export default {
  components: {
    Logo,
    Table
  }
}
</script>
