<template>
<div>
  <title>Fans</title>
  <!-- <h1 class="title">Hello</h1> -->

<section class="section">
    <div class="container">
<article class="message is-info">
  <div class="message-body">
  Starting April 13, every restaurants listed below will be listing a donation link where you can show your support by
  buying a gift cards (eGifts) from them. In return for your support, it will be offered at a discount.
  To reward early supporters, <strong>discount will be the highest at the beginning of this campaign.
    So don't hesitate to take action now!  </strong>   Every week, the discount rate will be lowered by 5% with a 5% floor. 
  </div>
</article>
    </div>

     <div class="container">
<article class="message is-danger">
  <div class="message-body">
  Over time, more restaurants will be added to the list as words spread. I would encourage you to keep monitoring this site.
  Or even better, you should reach out to the restaurants and tell them to sign up!
  </div>
</article>
    </div>
</section>
 


<body>
  <div class="container">
      <h6 class="title has-text-info"> Information</h6>
 <div class="tile">
  <div class="tile is-one-thirds">
    <Table></Table>
  </div>

  </div>

  <List></List>
  </div>
</body>
</div>
</template>

<script>
import Table from '~/components/Table'
import List from '~/components/List'
export default {
    components: {
        Table,
        List,
    }
}
</script>

<style>
h6
{
  margin-left: 15px;
}
</style>