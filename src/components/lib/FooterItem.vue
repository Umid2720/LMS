<template>
    <footer class="footer white">
        <div class="container flex justify-between">
            <div class="footer__box">
                <img src="@/assets/img/logo.png" alt="logo.png">
                <p class="l-s-1 mt-30 mb-50 medium">Language2Go — интерактивная платформа для легкого, удобного и
                    быстрого изучения иностранных языков.
                </p>
                <div class="flex c-gap-15 items-center">
                    <img src="@/assets/img/visa.png" alt="visa.png">
                    <img src="@/assets/img/mastercard.png" alt="mastercard.png">
                    <img src="@/assets/img/mir.png" alt="mir.png">
                </div>
            </div>
            <div class="footer__box bold">
                <div class="footer__title bold">Обучение</div>
                <ul>
                    <li><router-link to="/">Все языки</router-link></li>
                    <li><router-link to="/">Взрослым</router-link></li>
                    <li><router-link to="/">Детям и подросткам</router-link></li>
                    <li><router-link to="/">Мини-курсы</router-link></li>
                    <li><router-link to="/">Тренажеры</router-link></li>
                    <li><router-link to="/">Индивидуальные занятия</router-link></li>
                </ul>
            </div>
            <div class="footer__box bold">
                <div class="footer__title bold">Информация</div>
                <ul>
                    <li><router-link to="/">О нас</router-link></li>
                    <li><router-link to="/">Отзывы</router-link></li>
                    <li><router-link to="/">Новости</router-link></li>
                    <li><router-link to="/">Частые вопросы</router-link></li>
                    <li><router-link to="/">Условия оплаты</router-link></li>
                    <li><router-link to="/">Контакты</router-link></li>
                </ul>
            </div>
            <div class="footer__box bold">
                <div class="footer__title gibi">Контакты</div>
                <div class="footer__contact">+7 (495) 156-35-50</div>
                <div class="footer__email">
                    <a class="block l-s-1" href="mailto:info@language2go.ru">info@language2go.ru</a>
                    <a class="l-s-1" href="mailto:support@language2go.ru">support@language2go.ru</a>
                </div>
                <div class="footer__address l-s-1 mb-40">101000, Москва, Россия</div>
                <div class="flex items-center c-gap-15">
                    <a href="#" target="_blank"><img src="@/assets/img/fb.png" alt="facebook.png"></a>
                    <a href="#" target="_blank"><img src="@/assets/img/yt.png" alt="youtube.png"></a>
                    <a href="#" target="_blank"><img src="@/assets/img/vk.png" alt="vk.png"></a>
                    <a href="#" target="_blank"><img src="@/assets/img/tw.png" alt="twitter.png"></a>
                </div>
            </div>
        </div>
        <div class="footer__copy mt-100">
            <div class="container flex justify-between">
                <span class="l-s-1">© 2022 Language to go</span>
                <ul class="flex c-gap-40">
                    <li><router-link to="/">Правовая оговорка</router-link></li>
                    <li><router-link to="/">Пользовательское соглашение</router-link></li>
                    <li><router-link to="/">Политика конфиденциальности</router-link></li>
                </ul>
            </div>
        </div>
    </footer>
</template>
<script>
export default {

}
</script>
<style lang="scss">
@import '@/styles/components/footer.scss';
</style>