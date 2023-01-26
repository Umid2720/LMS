<template>
    <div class="container">
        <div class="flex items-end justify-between">
            <div class="col-6 col-md-12">
                <h2 class="letter-spacing">Курсы иностранных языков для любого уровня</h2>
            </div>
            <button class="btn outline">Все курсы</button>
        </div>

        <Splide class="mt-60 mb-100 course__slide" :options="{ type: 'loop', perPage: 3, autoplay: true, arrows: false, gap: 40 }">
            <SplideSlide>
                <CourseBox title="Немецкий для начального уровня" imgUrl="german.png" bgColor="#def1ff" />
            </SplideSlide>
            <SplideSlide>
                <CourseBox title="Китайский для среднего уровня" imgUrl="china.png" bgColor="#fdede4" />
            </SplideSlide>
            <SplideSlide>
                <CourseBox title="Испанский для среднего уровня" imgUrl="spain.png" bgColor="#efefff" />
            </SplideSlide>
            <SplideSlide>
                <CourseBox title="Немецкий для начального уровня" imgUrl="german.png" bgColor="#def1ff" />
            </SplideSlide>
            <SplideSlide>
                <CourseBox title="Китайский для среднего уровня" imgUrl="china.png" bgColor="#fdede4" />
            </SplideSlide>
            <SplideSlide>
                <CourseBox title="Испанский для среднего уровня" imgUrl="spain.png" bgColor="#efefff" />
            </SplideSlide>
        </Splide>
    </div>
</template>
<script>
import CourseBox from '../course/CourseBox.vue';
import { Splide, SplideSlide } from '@splidejs/vue-splide';

export default {
    components: {
        CourseBox, Splide,
        SplideSlide,
    }
}
</script>

