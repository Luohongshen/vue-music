<template>
  <m-header></m-header>
  <tab></tab>
  <router-view></router-view>
</template>

<script>
  // eslint-disable-next-line no-tabs
  // @/components/header/header
  // components/header/header.vue
import Header from '@/components/header/header'
import Tab from '@/components/tab/tab'
export default {
  components: {
    MHeader: Header,
    Tab
  }
}
</script>
