<template>
    <div class="col-6 col-sm-12 mb-40 for-whom__item" v-for="element of elements" :key="element.color">
        <div :style="{ 'background-color': element.color }" class="for-whom__icon b-r-50 flex items-center justify-center">
            <img :src="require('@/assets/img/' + element.src + '.png')" :alt="element.src">
        </div>
        <h3 class="mt-20 mb-10">{{ element.title }}</h3>
        <p class="medium l-s-2 grey">{{ element.text }}</p>
    </div>
</template>
<script>
export default {
    data() {
        return {
            elements: [
                { src: 'presentation', color: '#e3d2e7', title: 'Школьникам', text: 'Сдать выпускные экзамены или поступить в ВУЗ' },
                { src: 'graduation-cap', color: '#d5e9f6', title: 'Студентам', text: 'Переехать на обучение в другую страну или найти высокооплачеваемую работу' },
                { src: 'map', color: '#fff0cb', title: 'Эмигрантам', text: 'Адаптироваться в новой стране, создать конкурентное преимущество и трудоустроиться' },
                { src: 'commit', color: '#fad2d3', title: 'Общительным', text: 'Создать счастливую семью с иностранцем и интегрироваться в новое общество' },
                { src: 'briefcase', color: '#d5e9f6', title: 'Бизнесменам', text: 'Завести полезные знакомства среди иностранцев и масштабировать бизнес' },
                { src: 'ship', color: '#e4d3e8', title: 'Путешественникам', text: 'Свободно общаться и находить новых друзей, решать бытовые вопросы и спорные ситуации' }
            ]
        }
    },
}
</script>
<style lang="">
    
</style>