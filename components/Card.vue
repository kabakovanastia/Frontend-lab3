<template>
    <div class="card">
        <span>{{text}}</span>
    </div>
</template>
<script setup>
defineProps({
    text: String
})
</script>
<style scoped lang="sass">
@use './styles/mixins.sass' as mixins;
.card
    @include mixins.card(#071306, white)
    padding: 7px
    margin: 10px
</style>