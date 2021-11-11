<template>
    <main id="main_site">

            
        <!-- provvisorio, da completare/riempire prossimamente -->
        <div class="jumbotron">

            <!-- questo container potrebbe essere rimosso in fase di completamento del jumbotron -->
            <div class="container">

                <!-- testo provvisorio -->
                <h2>-->Content goes hear|--</h2>

            </div>

        </div>



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


    </main>
</template>

<script>
export default {
    name: 'MaineSite'
}
</script>

<style lang="scss" scoped>
.container{
    width: 70%;
    margin: auto;
    color: white;
}

.jumbotron{
    background-color: black;
    line-height: 100px;
}

.main_menu{
    height: 135px;
    background-color: blue;
    
    
    .container{
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-content: center;
    }

    .menu_card{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    img{
        max-width: 45px;
        max-height: 45px;
        margin: 0 10px;
    }

    a{
        font-size: 0.7rem;
        text-decoration: none;
        color: white;
    }
}

</style>