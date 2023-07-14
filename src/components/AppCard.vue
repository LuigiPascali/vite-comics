<script>

    export default {
        props: { cards: Array }
    };

</script>


<template>

    <ul>

        <li v-for="card in cards" :key="card.series" class="card">

            <div class="thumb">
                <img :src="card.thumb" :alt="card.series">
            </div>

            <div class="description">

                <div class="series">{{ card.series }}</div>
                
            </div>

        </li>

    </ul>

</template>


<style lang="scss" scoped>

    ul {
        display: flex;
        flex-wrap: wrap;
    }

    li {
        flex-basis: calc(100% / 6);
        padding: 10px;
    }

    li img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    .thumb {
        height: 280px;
    }

    .description {
        color: #ffffff;
        display: inline-block;
        margin-top: 10px;
    }

    .series {
        font-weight: 300;
        margin-bottom: 6px;
        text-transform: uppercase
    }

</style>