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
    
    <v-ons-card v-for="page of pages" :key="page.label"
                @click="push(page.component, page.label)"
            >
        <div class="title">{{ page.label }}</div>
        <div class="content">{{ page.desc }}</div>
        <v-ons-button modifier="quiet" class="button-margin">More ....</v-ons-button>
    </v-ons-card>
<v-ons-card v-for="page of pages" :key="page.label"
                @click="push(page.component, page.label)"
            >
        <div class="title">{{ page.label }}</div>
        <div class="content">{{ page.desc }}</div>
        <v-ons-button modifier="quiet" class="button-margin">More ....</v-ons-button>
    </v-ons-card>

<v-ons-card v-for="page of pages" :key="page.label"
                @click="push(page.component, page.label)"
            >
        <div class="title">{{ page.label }}</div>
        <div class="content">{{ page.desc }}</div>
        <v-ons-button modifier="quiet" class="button-margin">More ....</v-ons-button>
    </v-ons-card>

<v-ons-card v-for="page of pages" :key="page.label"
                @click="push(page.component, page.label)"
            >
        <div class="title">{{ page.label }}</div>
        <div class="content">{{ page.desc }}</div>
        <v-ons-button modifier="quiet" class="button-margin">More ....</v-ons-button>
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


