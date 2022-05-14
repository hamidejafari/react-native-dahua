<template id="main-page">
  <v-ons-page>
    <v-ons-tabbar  position="auto" :tabs="tabs">

    </v-ons-tabbar>
  </v-ons-page>
</template>
<script>
    import Home from './components/pages/Home.vue';
    import Profile from './components/pages/Profile.vue';
    import List from './components/pages/product/List.vue';
    import Warrantyinquiry from './components/pages/Warrantyinquiry.vue';
    import News from './components/pages/News.vue';
    import Buy from './components/pages/Buy.vue';
    import About from './components/pages/About.vue';
    import Service from './components/pages/Service.vue';

  export default {
    name : "app-tabbar",
    data () {
        return {
            tabs :[
                {
                    label : 'Home',
                    page : Home,
                    icon : 'ion-home'
                },
                {
                    label : 'Categories',
                    page : Profile,
                    icon:'ion-navicon'
                
                },
                {
                    label : 'ProductList',
                    page : List,
                    icon:'md-zoom-in'
                
                },
                {
                    label : 'WarrantyInquiry',
                    page : Warrantyinquiry,
                    icon:'ion-navicon'
                
                },
                {
                    label : 'News',
                    page : News,
                    icon:'ion-navicon'
                
                },
                {
                    label : 'Buy',
                    page : Buy,
                    icon:'ion-navicon'
                
                },
                 {
                    label : 'Service',
                    page : Service,
                    icon:'ion-navicon'
                
                },
                {
                    label : 'About',
                    page : About,
                    icon:'ion-navicon'
                
                }
            ]
        }
    },
    components:{
    }
  }
</script>
<style>

</style>


