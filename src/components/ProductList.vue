<template>
    <section class="products">
        Sono Lista prodotti
    </section>

</template>

<script>
export default {
    name: 'ProductList'
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/mixins' as*;
@use '../assets/styles/partials/variables' as*;

.products {
    padding: 4rem 1rem;
    text-align: center;
    background-image: url("../assets/img/fondo-pag-speciali.jpg");
}
</style>