<template>
  <HeaderItem/>
  <router-view />
  <FooterItem />
</template>

<script>
import HeaderItem from '@/components/lib/HeaderItem.vue';
import FooterItem from './components/lib/FooterItem.vue';
export default {
  components: {
    HeaderItem,
    FooterItem
}
}
</script>

<style lang="scss">
@import './styles/app.scss';
</style>

