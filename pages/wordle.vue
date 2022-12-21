<template>
    <InProcess/>
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
import InProcess from '../components/InProcess.vue';

export default {
    name: "WordlePersonalProjectPage",
    components: { InProcess }
}
</script>