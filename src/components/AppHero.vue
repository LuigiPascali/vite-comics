<script>

    export default {
        data() {
            return {
                
            }
        }
    }

</script>

<template>

    <div id="hero">

        <div class="container title">

            <div class="section">

                CURRENT SERIES

            </div>

        </div>
   
    </div>

</template>

<style lang="scss" scoped>

    #hero {
        position: relative;
        height: 300px;
        background-image: url(../assets/img/jumbotron.jpg);
        background-size: cover;
    }

    .title {
        color: #ffffff;
    }

    .section {
        position: absolute;
        top: 280px;
        width: 200px;
        padding: 10px 20px;
        background-color: #0282f9;
        color: #ffffff;
        font-weight: 900;
    }

</style>