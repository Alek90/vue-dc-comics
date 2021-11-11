<template>
    <header id="site_header">

        <div class="container">
            
            <!-- logo del brand -->
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>

            <!-- menu di navigazione del sito -->
            <nav id="site_menu">
                <a href="">CHARACTERS</a>
                <a href="">COMICS</a>
                <a href="">MOVIES</a>
                <a href="">TV</a>
                <a href="">GAMES</a>
                <a href="">COLLECTIBLES</a>
                <a href="">VIDEOS</a>
                <a href="">FANS</a>
                <a href="">NEWS</a>
                <a href="">SHOP</a>
            </nav>

        </div>

    </header>
</template>

<script>
export default {
    name: 'HeaderSite'
}
</script>

<style lang="scss" scoped>
.container{
    width: 70%;
    height: 100px;
    padding: 2px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .logo img{
        width: 70px;
    }

    nav{
        height: 94px;
    }

    a{
        display: inline-block;
        font-size: 0.6rem;
        font-weight: 800;
        line-height: 94px;
        color: rgb(70, 70, 70);
        text-decoration: none;
        margin: 0 12px;
    }

        
    a:hover{
        color: rgb(2, 130, 249);
        border-bottom: 3px solid rgb(2, 130, 249);
    }
}

</style>