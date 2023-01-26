<template>
    <div class="for-whom relative">
        <div class="container">
            <img src="@/assets/img/chat.png" alt="chat.png" class="absolute t-0 l-0">
            <div class="row">
                <div class="col-4 col-md-12">
                    <h2 class="mb-30">Кому подойдет <span>L2GO</span></h2>
                    <p class="mb-40">Language to go подойдет всем, кто хочет за короткий срок качественно изменить свою
                        жизнь, освоив
                        иностранный язык. lorem</p>
                    <button class="btn">Попробовать бесплатно</button>
                </div>
                <div class="col-8 col-md-12">
                    <div class="row">
                        <ForWhomItem />
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import ForWhomItem from '../for-whom/ForWhomItem.vue';

export default {
    components: {
        ForWhomItem
    }
}
</script>
<style lang="scss">
@import '@/styles/components/home/for-whom.scss';
</style>