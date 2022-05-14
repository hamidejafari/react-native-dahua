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
  
      <v-ons-list-item modifier="chevron" tappable>Iran</v-ons-list-item>
      <v-ons-list-item modifier="chevron" tappable>Iraq</v-ons-list-item>
      <v-ons-list-item modifier="chevron" tappable>American</v-ons-list-item>
      <v-ons-list-item modifier="chevron" tappable>China</v-ons-list-item>
      <v-ons-list-item modifier="chevron" tappable>Brezil</v-ons-list-item>
      <v-ons-list-item modifier="chevron" tappable>Swwiss</v-ons-list-item>
      <v-ons-list-item modifier="chevron" tappable>Chevron</v-ons-list-item>


    </v-ons-list>

     
   
  </v-ons-page>
</template>
<script>
  export default {
    
    name : "buy-list",
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


