<template>
     <div class="main-block">
        <Banner />
        <h1 class="title">Hello, world!</h1>
        <span>Look at my website</span>
        <div class="card-container">
            <Card text="Here"/>
            <Card text="And here"/>
            <Card text="And here here"/>
        </div>
    </div>
</template>
<script setup>
import Banner from './Banner.vue';
import Card from './Card.vue';
</script>
<style scoped lang="sass">
.main-block
    display: flex
    flex-direction: column
    flex-grow: 1
    background-color: #F4BF55
    margin: 10px
    padding: 10px
    align-items: center
    font-family: Montserrat, sans-serif
.card-container
    display: flex
    flex-direction: row
    padding-top: 20px
</style>