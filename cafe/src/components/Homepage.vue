<template>
    <div class="home_container">
        <img src="/static/logo.jpg" alt="Uni LOGO">
        <v-login></v-login>
        <v-category></v-category>
        

         <div class="nav-items">

              

                    <v-item ></v-item>
                
            </div>

    <div class="description container"></div>
        <h1>description</h1>
    </div>
</template>

<script>
import Login from "./Login"
import Category from "./Category"
import Item from "./Item"
export default {
  name: 'Homepage',
  data() {
      return {
          msg:"login",
      }
  },
  components:{
      'v-login':Login,
      'v-category': Category,
      'v-item':Item,
  },
}
</script>

<style>

</style>
