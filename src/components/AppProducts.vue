<script>

    import AppCards from './AppCards.vue';
    export default {
        components: { AppCards },

        data() {
            return {
            }
        }
    } 
</script>

<template>

    <div class="products">

        <div id="cards" class="container">

            <AppCards />

            <div class="footer">
                <a class="load_more">LOAD MORE</a>
            </div>

        </div>

    </div>

</template>


<style lang="scss" scoped>

    .products {
        background-color: black;
        padding-top: 50px;
    }

    .load_more {
        background-color: #0282f9;
        color: #ffffff;
        display: flex;
        justify-content: center;
        padding: 10px 20px;
        font-weight: 600;
        width: 20%;
        
    }

    .load_more:hover {
        background-color: #303030;
        color: #ffffff;
        cursor: pointer;
    }

</style>