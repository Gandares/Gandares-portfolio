<template>
  <MainPage/>
</template>

<style>
html{
  scroll-behavior: smooth;
}

body{
  padding: 0;
  margin: 0;
}
</style>

<script>
import MainPage from '../components/MainPage.vue';

export default {
    name: "IndexPage",
    components: { MainPage }
}
</script>