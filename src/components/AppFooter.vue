<script>

    export default {
        data() {
            return {

            }
        }
    }

</script>

<template>
        
    <div class="footer">

        <div class="container">

            <div class="button">

                <div class="left">
                    <a>SIGN-UP NOW!</a>
                </div>

                
                <div class="right">

                    <div><span>FOLLOW US</span></div>
                    <div><img src="../assets/img/footer-facebook.png" alt="facebook"></div>
                    <div><img src="../assets/img/footer-twitter.png" alt="twitter"></div>
                    <div><img src="../assets/img/footer-youtube.png" alt="youtube"></div>
                    <div><img src="../assets/img/footer-pinterest.png" alt="pinterest"></div>
                    <div><img src="../assets/img/footer-periscope.png" alt="periscope"></div>

                </div>

            </div>

        </div>

    </div>

</template>

<style lang="scss" scoped>

    .footer {
        background-color: #303030;
        height: 100px;
        padding: 20px 0;
        display: flex;
        justify-content: space-between;
        align-content: center;
        align-items: center;
    }

    .footer a {
        display: block;
        border: solid 2px #0282f9;
        padding: 10px 20px;
        color: #ffffff;
        cursor: pointer;
    }

    .footer a:hover {
        display: block;
        border: 2px solid #0282f9;
        background-color: #0282f9;
        padding: 10px 20px;
        color: #ffffff;
        cursor: pointer;
    }

    .button {
        display: flex;
        align-content: center;
        align-items: center;
        justify-content: space-between;
    }

    .right {
        display: flex;
        align-content: center;
        align-items: center;
        color: #0282f9;
        
    }

    .right span {
        margin-right: 20px;
        font-weight: bold;
    }

    .right img {
        padding: 0 14px;
        cursor: pointer;
    }

</style>