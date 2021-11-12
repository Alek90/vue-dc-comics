<template>
    <footer id="site_footer">

        <div class="footer_main">

            <div class="container">

                <div class="useful_links">

                    <div class="comics">

                        <h4>DC COMICS</h4>

                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>

                        <h4>SHOP</h4>

                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC ollectibles</li>
                        </ul>

                    </div>

                    <div class="dc">

                        <h4>DC</h4>

                        <ul>
                            <li>Terms Of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>

                    </div>

                    <div class="sites">

                        <h4>SITES</h4>

                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>

                    </div>

                </div>

                <div class="pattern_logo">
                </div>
                
            </div>

        </div>
        

        <div class="icons_footer">

            <div class="container">

                <button class="sing_up">
                    SING-UP NOW!
                </button>

                <div class="social">

                    <div class="social_invite">
                        FOLLOW US
                    </div>

                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">

                </div>

            </div>
            
        </div>

    </footer>
</template>

<script>
export default {
    name: 'FooterSite'
}
</script>

<style lang="scss" scoped>
.container{
    height: 100%;
    display: flex;
    justify-content: space-between;
}

.footer_main{
    height: 300px;
    color: white;
    background-color: rgb(48, 48, 48);
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top;
    
    .useful_links{
        width: 30%;
        padding: 20px 0;
        display: flex;
        justify-content: space-between;
    }

    h4{
        line-height: 3rem;
    }

    ul{
        list-style: none;
        font-size: 0.6rem;
        line-height: 1rem;
        color: rgb(149, 149, 149);

        li:hover{
            color: rgb(2, 130, 249);
        }
    }

    .pattern_logo{
        width: 42%;
        height: 100%;
        background-image: url(../assets/img/dc-logo-bg.png);
        background-position: center;
        background-size: cover;
        background-repeat: no-repeat;
    }

}

.icons_footer{
    height: 100px;
    font-weight: 600;
    background-color: rgb(48, 48, 48);

    .container{
        align-items: center;
    }

    .sing_up{
        padding: 10px;
        font-weight: 600;
        color: white;
        background-color: transparent;
        border: 1px solid rgb(2, 130, 249);

        &:hover{
            background-color: rgb(2, 130, 249);
            box-shadow: 0 0 2px 2px white;
           
        }
    }

    .social{
        width: 28%;
        color: rgb(2, 130, 249);
        display: flex;
        justify-content: space-between;
        align-items: center;

        img{
            width: 30px;

            &:hover{
                opacity: (70%);
                border-radius: 50%;
                box-shadow: 0 0 1px 1px rgb(2, 130, 249), 0 0 3px 3px white;
            }
        }
    }
}


</style>