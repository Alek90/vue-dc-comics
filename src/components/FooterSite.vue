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
                    SING-UP NOW
                </button>

                <div class="social">

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
    width: 70%;
    margin: auto;
    display: flex;
    justify-content: space-between;

}

.footer_main{
    height: 300px;
    color: white;
    background-color: darkslategray;
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top;

    .container{
        height: 100%;
    }
    
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

</style>