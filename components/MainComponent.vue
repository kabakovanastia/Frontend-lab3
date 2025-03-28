<template>
    <div class="main-cont">
        <HeaderComponent />
        <div class="main">
            <LeftSide />
            <MainPage />
            <RightSide />
        </div>
        <FooterComponent />
    </div>
</template>
<script setup>
import HeaderComponent from './HeaderComponent.vue';
import LeftSide from './LeftSide.vue';
import MainPage from './MainPage.vue';
import RightSide from './RightSide.vue';
import FooterComponent from './FooterComponent.vue';
</script>
<style scoped lang="sass">
.main-cont
    display: flex
    flex-direction: column
    height: 97vh
    font-size: 1.6rem
    font-family: Open Sans, sans-serif
.main
    display: flex
    flex-direction: row
    justify-content: space-between
    flex-grow: 1
</style>