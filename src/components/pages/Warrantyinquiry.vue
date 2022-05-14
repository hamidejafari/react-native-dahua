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
     <v-ons-list>
          <v-ons-list-header style="text-transform: none;font-size: 18px;padding-left: 35px;padding-bottom: 10px;padding-top: 10px;">WarrantyInquiry </v-ons-list-header>
          <v-ons-list-item :modifier="md ? 'nodivider' : ''">
            <div class="left">
              <v-ons-icon icon="on-navicon" class="list-item__icon"></v-ons-icon>
            </div>
            <label class="center">
              <v-ons-input float maxlength="20"
                placeholder="Serial Number"
                v-model="serialNumber"
              >
              </v-ons-input>
            </label>
          </v-ons-list-item>
         <v-ons-list-item>
             <section style="margin: 16px">
              
                  <v-ons-button style="padding: 10px 200px;background: red" modifier="large" class="button-margin">Large</v-ons-button>
                <br>
                  <v-ons-button style="padding: 10px 200px;background: green;" modifier="large" class="button-margin">Large</v-ons-button>

            </section>
          </v-ons-list-item>

          <v-ons-list-item>
            <div class="left left-label" style="padding-left: 25px;">
             Serial :  {{ serialNumber || 'None' }}
            </div>
          </v-ons-list-item>
          <v-ons-list-item>
            <div class="left left-label"  style="padding-left: 25px;" >
             Serial :  
            </div>
          </v-ons-list-item>
          <v-ons-list-item>
            <div class="left left-label"   style="padding-left: 25px;">
             Serial :  
            </div>
          </v-ons-list-item>

       


          






    

          
    

        
    </v-ons-list>    
    
      <v-ons-card v-for="page of pages" :key="page.label"
                  @click="push(page.component, page.label)"
                >
                  <div class="title">{{ page.label }}</div>
                  <div class="content">{{ page.desc }}</div>
            </v-ons-card>


   
  </v-ons-page>
</template>
<script>
import Home from './Home';
  export default {
    name : "warranty-inquiry",
      data() {
    return {
      serialNumber: '',
       pages: [
        {
          component: Home,
          label: 'Pull Hook',
          desc: 'Simple "pull to refresh" functionality to update data.'
        }
      ]
    };
  }
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


