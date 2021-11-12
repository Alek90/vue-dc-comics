<template>
    <div class="comic_cover">

        <div class="card">

            <img :src="cover" alt="">

            <div class="text_title">

                <p>{{series}}</p>

            </div>

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

        .text_title{
            width: 100%;
            height: 30%;
            padding-top: 20px;
            font-size: 0.9rem;
            background-color: rgb(28, 28, 28);
            position: absolute;
            bottom: 0;
            left: 0;
        }

    
       
    }
</style>