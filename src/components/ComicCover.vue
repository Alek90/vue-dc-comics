<template>
    <div class="comic_cover">
        <img :src="cover" alt="">
        <p>{{series}}</p>
    </div>
</template>

<script>
export default {
    props:{
        cover: String,
        series: String
    }
}
</script>

<style lang="scss" scoped>

</style>