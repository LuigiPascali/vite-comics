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

                <div class="right">
                    <a>SIGN-UP NOW!</a>
                </div>

                
                <div class="left">

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
        color: white;
        cursor: pointer;
    }

    .footer a:hover {
        display: block;
        border: 2px solid #0282f9;
        background-color: #0282f9;
        padding: 10px 20px;
        color: white;
        cursor: pointer;
    }

    .button {
        display: flex;
        align-content: center;
        align-items: center;
        justify-content: space-between;
    }

    .left {
        display: flex;
        align-content: center;
        align-items: center;
        color: #0282f9;
        cursor: pointer;
    }

    .left span {
        margin-right: 20px;
    }

    .left img {
        padding: 0 14px;
    }

</style>