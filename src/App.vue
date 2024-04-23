<template>
  <div>
    <AppHeader />
    <AppMain />
    <AppCard />
    <AppFooter />

  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppCard from './components/AppCard.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    AppCard,
  },
  data() {


    return {}
  }
}
</script>

<style lang="scss">
@use './assets/general'
</style>