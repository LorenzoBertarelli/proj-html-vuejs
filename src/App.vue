<script>
import AppHeader from './components/AppHeader.vue';
import AppCounter from './components/AppCounter.vue';
import AppAboutMe from './components/AppAboutMe.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppCounter,
    AppAboutMe,
    AppFooter
},
}
</script>

<template>
  <AppHeader />
  <AppCounter />
  <AppAboutMe />
  <AppFooter />
</template>

<style lang="scss">
@use "./style/general.scss" as *
</style>
