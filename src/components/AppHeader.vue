<script>

    export default {
        data() {
            return {
                links: [
                    {
                        text: 'Characters',
                        url: '#',
                        current: false,
                    },
                    {
                        text: 'Comics',
                        url: '#',
                        current: true,
                    },
                    {
                        text: 'Movies',
                        url: '#',
                        current: false,
                    },
                    {
                        text: 'TV',
                        url: '#',
                        current: false,
                    },
                    {
                        text: 'Games',
                        url: '#',
                        current: false,
                    },
                    {
                        text: 'Collectibles',
                        url: '#',
                        current: false,
                    },
                    {
                        text: 'Videos',
                        url: '#',
                        current: false,
                    },
                    {
                        text: 'Fans',
                        url: '#',
                        current: false,
                    },
                    {
                        text: 'News',
                        url: '#',
                        current: false,
                    },
                    {
                        text: 'Shop',
                        url: '#',
                        current: false,
                    },
                ],
            }
        }
    }

</script>

<template>

    <header>

        <nav class="container">

            <div>
                <img src="../assets/img/dc-logo.png" alt="Logo_DC" class="logo">
            </div>

            <div>

                <ul>

                    <li v-for="link in links" :key="link.text">
                        <a :href="link.url" :class="{ active: link.current }">
                            {{ link.text }}
                        </a>
                    </li>

                </ul>

            </div>

        </nav>

    </header>

</template>

<style lang="scss" scoped>

    header {height: 100px; margin: 10px auto;}

    nav {display: flex; justify-content: space-between; align-items: center;}

    .logo {width:80px;}

    ul {
        display: flex;
        justify-content: space-between;
        align-items: center;
        list-style-type: none;

        li {
            list-style: none;
            position: relative;
            font-family: 'Open San Variable', sans-serif;
            font-weight: 700;
            text-transform: uppercase;
        }

        a {
            padding: 10px 20px;

            &active {
                background-color: rgba(2, 130, 250, 1);
                color: #ffffff;
            }

            &:hover::after {
                content: "-";
                background-color: #0282f9;
                display: block;
                width: 100%;  
                position: absolute;
                top: 40px;
                left: 0px;
                right: 0px;
                font-size: .25rem;
            }
        }

    }

</style>