<template>
  <v-ons-page>
    <v-ons-toolbar>
      <div class="center my-center">Dahua | dahua.ir</div>
      <div class="right my-right">
      </div>
      <div class="left my-left">
          <v-ons-toolbar-button class="my-btn" icon="ion-navicon, material: md-menu"></v-ons-toolbar-button>
      </div>
    </v-ons-toolbar>  
   
    <v-ons-list>
        <v-ons-list-item  modifier="chevron" tappable>
            <div class="left">
            <img class="list-item__thumbnail" src="../../../assets/dahua-product.jpg" style="height:100px;width:100px" />
            </div>
            <div class="center">
            <span class="list-item__title">Product of Dahua</span><span class="list-item__subtitle">Network Camera</span>
            </div>
        </v-ons-list-item>
        <v-ons-list-item  modifier="chevron" tappable>
            <div class="left">
            <img class="list-item__thumbnail" src="../../../assets/dahua-product2.jpg" style="height:100px;width:100px" />
            </div>
            <div class="center">
            <span class="list-item__title">Product of Dahua</span><span class="list-item__subtitle">Network Camera</span>
            </div>
        </v-ons-list-item>
        <v-ons-list-item  modifier="chevron" tappable>
            <div class="left">
            <img class="list-item__thumbnail" src="../../../assets/dahua-product3.jpg" style="height:100px;width:100px" />
            </div>
            <div class="center">
            <span class="list-item__title">Product of Dahua</span><span class="list-item__subtitle">Network Camera</span>
            </div>
        </v-ons-list-item>
        <v-ons-list-item  modifier="chevron" tappable>
            <div class="left">
            <img class="list-item__thumbnail" src="../../../assets/dahua-product4.jpg" style="height:100px;width:100px" />
            </div>
            <div class="center">
            <span class="list-item__title">Product of Dahua</span><span class="list-item__subtitle">Network Camera</span>
            </div>
        </v-ons-list-item>

    </v-ons-list>
   
  </v-ons-page>
</template>
<script>
  export default {
    
    name : "product-list",
  }
</script>
<style>
 
  .my-center{
    background: #f04545;
    color : white
  }
  .my-btn{
    color : white
  }
  .my-right{
    background: #f04545;
  }
  .my-left{
    background: #f04545;
  }
</style>


