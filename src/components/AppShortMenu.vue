<script>

   export default {
    data() {
      return{
        dcLinks: [
            {
                nome: 'Characters',
                link: '',
            },
            {
                nome: 'Comics',
                link: '',
            },
            {
                nome: 'Movies',
                link: '',
            },
            {
                nome: 'Tv',
                link: '',
            },
            {
                nome: 'Games',
                link: '',
            },
            {
                nome: 'Collectibles',
                link: '',
            },
            {
                nome: 'Videos',
                link: '',
            },
            {
                nome: 'News',
                link: '',
            },

        ],
        shopLinks: [
            {
                nome: 'Shop DC',
                link: '',
            },
            {
                nome: 'Shop DC Collectibles',
                link: '',
            },
        ],
        dcLinks: [
            {
                nome: 'Terms of Use',
                link: '',
            },
            {
                nome: 'Privacy policy',
                link: '',
            },
            {
                nome: 'Ad Choices',
                link: '',
            },
            {
                nome: 'Advertising',
                link: '',
            },
            {
                nome: 'Jobs',
                link: '',
            },
            {
                nome: 'Subscriptions',
                link: '',
            },
            {
                nome: 'Talent Workshop',
                link: '',
            },
            {
                nome: 'CPSC Cetficates',
                link: '',
            },
            {
                nome: 'Rating',
                link: '',
            },
            {
                nome: 'Shop Help',
                link: '',
            },
            {
                nome: 'Contact Us',
                link: '',
            },
        ],
        sitesLinks: [
        {
                nome: 'DC',
                link: '',
            },
            {
                nome: 'MAD Magazine',
                link: '',
            },
            {
                nome: 'DC Kids',
                link: '',
            },
            {
                nome: 'DC Universe',
                link: '',
            },
            {
                nome: 'DC Power Visa',
                link: '',
            },
        ]
      }
    },
    
  }
</script>

<template>

    <div class="short_menu">

        <div class="container short_menu_bg">
            
            <div class="short_menu_link">

                <div>

                    <ul id="dc-comics">

                        <li>
                            <h3>DC COMIC</h3>
                        </li>
                        <li v-for="links in dcLinks">
                            <a href="#" >
                                {{links.nome}}
                            </a>
                        </li>

                    </ul>

                    <ul id="shop">

                        <li>
                            <h3>SHOP</h3>
                        </li>
                        <li v-for="links in shopLinks">
                            <a href="#">
                            {{links.nome}}
                            </a>
                        </li>

                    </ul>

                </div>
                
                <div class="short_menu_link">

                    <ul id="DC">

                        <li>
                            <h3>DC</h3>
                        </li>
                        <li v-for="links in dcLinks">
                            <a href="#">
                                {{ links.nome }}
                            </a>
                        </li>

                    </ul>

                </div>
                
                <div class="short_menu_link">

                    <ul id="sites">

                        <li>
                            <h3>SITE</h3>
                        </li>
                        <li v-for="links in sitesLinks">
                            <a href="#">
                                {{ links.nome }}
                            </a>
                        </li>

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