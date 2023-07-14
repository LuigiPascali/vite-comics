<script>
    export default {
        data() {
            return {

            }
        }
    }

</script>

<template>

    <div class="logos">

        <div>

            <div class="items">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics">
                <p>DIGITAL COMICS</p>
            </div>

        </div>

        <div>

            <div class="items">
                <img src="../assets/img/buy-comics-merchandise.png" alt="DC Merchandise">
                <p>DC MERCANDISE</p>
            </div>

        </div>

        <div>

            <div class="items">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscription">
                <p>SUBSCRIPTION</p>
            </div>

        </div>

        <div>

            <div class="items">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="Shop Locator">
                <p>COMIC SHOP LOCATOR</p>
            </div>

        </div>

        <div>

            <div class="items">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="DC Power Visa">
                <p>DC POWER VISA</p>
            </div>

        </div>

    </div>

</template>

<style lang="scss" scoped>

    .logos {
        background-color: #0282f9;
        height: 150px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .logos img {
        display: block;
        height: 50px;
        padding: 0 12px;
    }

    .logos .items {
        display: flex;
        justify-content: space-between;
        align-content: center;
        align-items: center;
        color: #ffffff;
        cursor: pointer;
    }

</style>