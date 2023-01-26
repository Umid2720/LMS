<template>
    <div class="course__box" :style="{ 'background-color': bgColor }">
        <img :alt="imgUrl" class="block mb-20" :src="require('@/assets/img/' + imgUrl)" />
        <router-link to="/" class="course__title bold letter-spacing">{{ title }}</router-link>
        <div class="course__info letter-spacing grey mt-20">Длительность: <b class="black bold">45 часов</b></div>
        <div class="course__info l-s-1 grey">Модулей: <b class="black bold">3</b></div>
        <div class="course__bottom flex items-center semibold justify-between">
            <router-link to="/" class="router__more flex items-center letter-spacing">
                Узнать подробнее
                <img src="@/assets/img/arrow-right.png" class="ml-10">
            </router-link>
            <div class="course__price bold black">От 6 520 Р</div>
        </div>
    </div>
</template>
<script>
export default {
    props: ['title', 'imgUrl', 'bgColor'],
}
</script>
<style lang="scss">
@import '@/styles/components/course.scss';
</style>