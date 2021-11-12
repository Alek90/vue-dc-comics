<template>
    <div class="comic_cover">

        <div class="card">

            <img :src="cover" alt="">
            <p>{{series}}</p>

        </div>
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

<style lang="scss">
 .comic_cover{
    width: calc(100% / 7);
    margin: 10px;

        .card{
            width: 100%;
            position: relative;

        }

        img{
            width: 100%;
        }

        /* 
    p{
        width: 100%;
        background-color: rgb(28, 28, 28);
        position: absolute;
        bottom: 0;
        left: 0;
    }
 */
}
</style>