<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import ConnectionLinks from './components/ConnectionLinks.vue';
import AppFooter from './components/AppFooter.vue';
import SocialLinks from './components/SocialLinks.vue';


export default{
    data(){
        return{

        }
    },
    components:{
      AppHeader,
      AppMain,
      ConnectionLinks,
      AppFooter,
      SocialLinks
    }
}

</script>

<template>
  <AppHeader />
  <AppMain />
  <ConnectionLinks />
  <AppFooter />
  <SocialLinks />
</template>

<style scoped>

</style>
