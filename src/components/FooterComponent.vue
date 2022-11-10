<template>
    <footer>
        <div class=" cols container">
            <a href="#" class="logo">
                <img src="../assets/img/la-molisana-logo.png" alt="La Molisana">
            </a>
            <div class="footer-links">
                <h4>Pastificio</h4>
                <nav>
                    <ul>
                        <li><a href="#">Il Pastificio</a></li>
                        <li><a href="#">Il Pastificio</a></li>
                        <li><a href="#">Il Pastificio</a></li>
                        <li><a href="#">Il Pastificio</a></li>
                        <li><a href="#">Il Pastificio</a></li>
                    </ul>
                </nav>
            </div>
            <div class="footer-links">

            </div>

        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterComponent'
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/mixins' as*;
@use '../assets/styles/partials/variables' as*;

footer {
    padding-top: 3rem;

    .cols {
        display: flex;
        margin-bottom: 3rem;

        .logo,
        .footer-llinks {
            flex-basis: calc(100% /3);
            padding: 0 1rem;
        }
    }
}
</style>