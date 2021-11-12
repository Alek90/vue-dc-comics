<template>
    <!-- menu del corpo della pagina -->
    <nav class="main_menu">

        <div class="container">
   
            <div class="menu_card">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <a href="">DIGITAL COMICS</a>
            </div>

            <div class="menu_card">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <a href="">DC MERCHANDAISE</a>
            </div>

            <div class="menu_card">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <a href="">SUBSCRIPTION</a>
            </div>

            <div class="menu_card">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <a href="">COMIC SHOP LOCATOR</a>
            </div>

            <div class="menu_card">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <a href="">DC POWER VISA</a>
            </div>

        </div>

    </nav>
    
</template>

<script>
export default {
    name: 'MainMenu'
}
</script>

<style lang="scss" scoped>

.main_menu{
    height: 135px;
    background-color: rgb(2, 130, 249);

    .container{
        height: 100%;
        display: flex;
        justify-content: space-around;
        align-content: center;
    }

    .menu_card{
        width: calc(100% / 6);
        display: flex;
        justify-content: center;
        align-items: center;

        &:hover{
            background-color: rgb(2, 130, 249);
        }

        &:hover img{
            max-width: 55px;
            max-height: 55px;
        }

        &:hover a{
            font-size: 0.8;
            font-weight: 800;
            text-decoration: underline;
        }
    }

    img{
        max-width: 45px;
        max-height: 45px;
        margin-right: 8px;
    }

    a{
        font-size: 0.7rem;
        text-decoration: none;
        color: white;
    }

}
</style>