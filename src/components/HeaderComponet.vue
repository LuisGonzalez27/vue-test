<template>
    <header>
        {{ titolo }}
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent',
    data() {
        return {
            titolo: 'Header ,sono un componente!'
        }
    }
}
</script>

<style lang="css">
header {
    width: 100%;
    height: 70px;
    background-color: black;
    padding: 20px;
    color: white;
}
</style>