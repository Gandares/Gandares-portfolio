<template>
    <PagePersonalWordle/>
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
import PagePersonalWordle from '../components/Personal_projects/wordlePage/PagePersonalWordle.vue';

export default {
    name: "Wordle",
    components: { PagePersonalWordle }
}
</script>