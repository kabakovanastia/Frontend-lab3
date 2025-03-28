<template>
    <div class="banner">
        <span>Banner</span>
    </div>
</template>
<style scoped lang="sass">
@use './styles/mixins.sass' as mixins;
.banner
    @include mixins.card(#f1cf8c)
    width: 95%
    padding: 5px
</style>