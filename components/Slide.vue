<template>
    <div class="slide" v-editable="blok">
        <img :src="blok.image">
    </div>
</template>

<script>
    export default {
        props: ['blok']
    }
</script>

<style lang="scss">
    .slide{

    margin: 0;
    padding: 0;}
    .slide img {
        width: 100%;
        height: 300px;
        background-position: center;
        background-size: cover

    }
</style>