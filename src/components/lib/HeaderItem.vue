<template>
    <header class="header flex items-center">
        <router-link to="/"><img src="@/assets/img/logo.svg" alt="logo.svg" class="logo"></router-link>
        <nav class="navbar">
            <ul class="menu__list flex">
                <li class="menu-item">
                    <router-link to="/">Курсы</router-link>
                </li>
                <li class="menu-item">
                    <router-link to="/">О нас</router-link>
                </li>
                <li class="menu-item">
                    <router-link to="/">Блог</router-link>
                </li>
                <li class="menu-item">
                    <span class="pointer">Еще</span>
                    <ul class="header__dropdown none">
                        <li><router-link to="/">faq</router-link></li>
                        <li><router-link to="/">Контакты</router-link></li>
                        <li><router-link to="/">Условия оплаты</router-link></li>
                    </ul>
                </li>
            </ul>
        </nav>
        <button class="btn">Войти</button>
    </header>
</template>
<script>
export default {

}
</script>
<style lang="scss">
@import '@/styles/components/header.scss';
</style>