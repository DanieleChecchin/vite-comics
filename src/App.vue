<script>

import AppHeader from './components/AppHeader.vue';
import AppBanner from './components/AppBanner.vue';
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
      AppBanner,
      AppMain,
      ConnectionLinks,
      AppFooter,
      SocialLinks
    }
}

</script>

<template>
  <AppHeader />
  <AppBanner />
  <AppMain />
  <ConnectionLinks />
  <AppFooter />
  <SocialLinks />
</template>

<style lang="scss">
@use "./styles/general.scss" as *;


</style>
