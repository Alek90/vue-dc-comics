<template>
    <div class="comic_cover">
        <img :src="cover" alt="">
        <p>{{series}}</p>
    </div>
</template>

<script>
export default {
    name: 'ComicCover',
    props:{
        cover: String,
        series: String
    }
}
</script>

<style lang="scss" scoped>
.comic_cover{

    img{
        height: 200px;

    }
}

</style>