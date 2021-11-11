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
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;

    a{
        font-size: 0.7rem;
        font-weight: 800;
        color: darkslategray;
        text-decoration: none;
        margin: 0 12px;
    }
}

</style>