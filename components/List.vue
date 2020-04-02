<template>
<body>
  <section class="section">
    <div class="container">
      <div v-for="restaurant in restaurants" :key="restaurant.URL"  class="columns">
        <div class="column ">
        <div class="card has-background-warning ">
            <div class="card-content has-text-centered ">
              <div class="content ">
                  <p class="title has-text-weight-bold has-text-black">
                    {{ restaurant.name }}
                  </p>
                <!-- <p class="subtitle">Seattle </p>   -->
                <p class='subtitle'> {{ restaurant.city }}</p>

                <a :href="restaurant.URL" target="_blank"> <button class="button is-danger">Buy</button></a>
              </div>
            </div>

        </div>
      </div>

      </div>
    </div>
  </section>
    </body>

</template>

<script>
export default {
    data() {
      return {
        restaurants: [
      {
        "name": "Rockcreek",
        "city": "Seattle",
        "URL": "https://rockcreekseattle.com/store/product/gift-card/"
      },
        {
        "name": "Oddfellows",
        "city": "Seattle",
        "URL": "http://www.thederschanggroup.com/store/gift-card"
      },
        {
        "name": "Soi",
        "city": "Capitol Hill",
        "URL": "https://tilwedine.com/"
      },
        {
        "name": "Sawyer",
        "city": "Ballard",
        "URL": "https://www.toasttab.com/sawyer-restaurant/giftcards"
      },
        {
        "name": "Eight Row",
        "city": "Seattle",
        "URL": "https://squareup.com/gift/XVX5J5YM7ZD7M/order/"
      },
        {
        "name": "Kedai Makan",
        "city": "Seattle",
        "URL": "http://www.kedaimakansea.com/gift-certificates"
      },
        
    ]
        }
    },

}
</script>





<style scoped>
.button:hover {
  background-color: hsl(141, 71%, 48%);
}
</style>
