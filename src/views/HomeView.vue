<template>
  <div class="home">
    <WelcomeItem />
    <CourserList/>
  </div>
</template>

<script>
import CourserList from '@/components/home/CourserList.vue';
import WelcomeItem from '@/components/home/WelcomeItem.vue';


export default {
  name: 'HomeView',
  components: {
    WelcomeItem,
    CourserList
}
}
</script>

<style lang="scss">

</style>
