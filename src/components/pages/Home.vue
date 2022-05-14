<template >
  <v-ons-page>
    <v-ons-toolbar>
      <div class="center my-center">Dahua | dahua.ir</div>
      <div class="right my-right">
      </div>
      <div class="left my-left">
          <v-ons-toolbar-button class="my-btn" icon="ion-navicon, material: md-menu"></v-ons-toolbar-button>
      </div>
    </v-ons-toolbar>  
    <img class="img-logo" src="../../assets/LOGO111.png" style="width:150px">
    <br><br><br>
    <div class="row">
      <div class="col-md-6" style="float: right;padding-right: 10%;">
        <v-ons-card style="background:none;box-shadow: none;">
          <div class="center">
            <img src="../../assets/logo1.png"  alt="Onsen UI" style="width:100px;">
          </div>
          <div class="title" style="text-align:center;font-size:20px">
            Products
          </div>
        </v-ons-card>
      </div>
      <div class="col-md-6"  style="float: left;padding-left: 10%;">
        <v-ons-card style="background:none;box-shadow: none;">
          <div class="center">
            <img src="../../assets/logo2.png"  alt="Onsen UI" style="width:100px;padding-left: 20px;">
          </div>
          <div class="title" style="text-align:center;font-size:20px">
            Warranty inquiry
          </div>
        </v-ons-card>
      </div>
    </div>
    
    
   
  </v-ons-page>
</template>
<script>
  export default {
    name : "home",
  }
</script>
<style>
  .img-logo{
    padding-left: 35%;
    padding-top: 10%;
  }
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


