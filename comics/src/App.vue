<script>
import AppHeader  from './components/AppHeader.vue';
import AppMain  from './components/AppMain.vue';
import AppFooter  from './components/AppFooter.vue';

export default {
    name:'App',
    components:{
    AppHeader,
    AppMain,
    AppFooter,
}
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />

</template>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

</style>
