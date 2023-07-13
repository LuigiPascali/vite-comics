<script>

    export default {
        data() {
            return {
                
            }
        }
    }

</script>

<template>

    <div class="short_menu">

        <div class="container short_menu_bg">
            
            <div class="short_menu_link">

                <div>

                    <ul id="dc-comics">
                        <li>
                            <h3>DS COMIC</h3>
                        </li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Video</li>
                        <li>News</li>
                    </ul>

                    <ul id="shop">
                        <li>
                            <h3>SHOP</h3>
                        </li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>

                </div>
                
                <div class="short_menu_link">

                    <ul id="DC">

                        <li>
                            <h3>DC</h3>
                        </li>
                        <li>Terms Of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>alent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Retings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>

                    </ul>

                </div>
                
                <div class="short_menu_link">

                    <ul id="sites">

                        <li>
                            <h3>SITE</h3>
                        </li>
                        <li>DC</li>
                        <li>MAD Magazione</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power visa</li>

                    </ul>

                </div>

            </div>

        </div>

    </div>

</template>

<style lang="scss" scoped>

    .short_menu {
        background-color: #303030;
        color: #959595;
        height: 400px;
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
    }

    .short_menu_bg {
        height: 100%;
        background-image: url(../assets/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-position: right;
    }

    .short_menu h3 {
        margin-bottom: 10px;
        margin-top: 40px;
    }

    .short_menu_link {
        display: flex;
        margin: 0px 40px;
    }

</style>