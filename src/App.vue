<template>
  <div>
    <AppHeader />
    <AppMain />
    <AppCard />
    <AppBigCard />
    <AppForumCard />
    <AppFooter />

  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppCard from './components/AppCard.vue';
import AppBigCard from './components/AppBigCard.vue';
import AppForumCard from './components/AppForumCard.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
  data() {


    return {}
  }
}
</script>

<style lang="scss">
@use './assets/general'
</style>