<template>
    <main id="main_site">

            
        <div class="jumbotron">
            <!-- sfondo comics -->
        </div>

        <!-- vetrina con le copertine delle serie correnti -->
        <ComicsSeries />

        
        <!-- menu del corpo della pagina -->
        <MainMenu />

    </main>
</template>


<script>
import ComicsSeries from './ComicsSeries.vue'
import MainMenu from './MainMenu.vue'

export default {
    name: 'MaineSite',
    components: {
        ComicsSeries,
        MainMenu
    }
}
</script>

<style lang="scss" scoped>
#main_site{
    color: white;

    .jumbotron{
        height: 350px;
        background-image: url(../assets/img/jumbotron.jpg);
        background-size: cover;
        background-position: top;
        background-repeat: no-repeat;
    }

    
}

</style>