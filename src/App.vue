<template>
  <HeaderComponent />
  <h1>{{ message }}</h1>
  <FooterComponent />
</template>

<script>
import HeaderComponent from './components/HeaderComponet.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
  components: {
    HeaderComponent,
    FooterComponent
  },
  data() {
    return {
      message: 'Hello Vite!',
    }
  },
  methods: {

  },
}
</script>

<style lang="css">
h1 {
  color: red;
  padding: 20px;
}
</style>