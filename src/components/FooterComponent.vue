<template>
    <footer>
        {{ titolo }}
    </footer>
</template>

<script>
export default {
    name: 'FooterComponent',
    data() {
        return {
            titolo: 'Footer, sono un componente'
        }
    }
}
</script>

<style lang="css">
footer {
    width: 100%;
    height: 70px;
    background-color: yellow;
    padding: 20px;
}
</style>