<template>
  <div class="home">
    <WelcomeItem />
    <CourserList/>
    <ForWhom />
  </div>
</template>

<script>
import CourserList from '@/components/home/CourserList.vue';
import ForWhom from '@/components/home/ForWhom.vue';
import WelcomeItem from '@/components/home/WelcomeItem.vue';


export default {
  name: 'HomeView',
  components: {
    WelcomeItem,
    CourserList,
    ForWhom
}
}
</script>
<style>
@import '@splidejs/vue-splide/css';
</style>