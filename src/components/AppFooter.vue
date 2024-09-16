<script>
export default{
    data(){
        return{
            leftLinksUp:[
                'Characters',
                'Comics',
                'Movies',
                'TV',
                'Games',
                'Videos',
                'News'
            ],

            leftLinksDown:[
                'Shop DC',
                'Shop DC Collectibles'
            ],

            centerLinks:[
                'Terms Of Use',
                'Privacy policy (New)',
                'Ad Choices',
                'Advertising',
                'Job',
                'Subscriptions',
                'Talent Workshops',
                'CPSC Certificates',
                'Ratings',
                'Shop Help',
                'Contact Us'
            ],

            rightLinks:[
                'DC',
                'MAD Magazine',
                'DC Kids',
                'DC Universe',
                'DC Power Visa'
            ]

        }
    }
}
</script>

<template>
    <footer>
        <div class="container">
            <div class="left-footer">
            <h5>DC COMICS</h5>
            <ul>
                <li v-for="leftLink in leftLinksUp"> {{ leftLink }} </li>
            </ul>
            <h5>SHOP</h5>
            <ul>
                <li v-for="leftLink in leftLinksDown">{{ leftLink }}</li>
                
            </ul>
            </div>
            <div class="center-footer">
            <h5>DC</h5>
            <ul>
                <li v-for="centerLink in centerLinks">{{ centerLink }}</li>  
            </ul>
            </div>
            <div class="right-footer">
            <h5>SITES</h5>
            <ul>
                <li v-for="rightLink in rightLinks">{{ rightLink }}</li>
            </ul>
            </div>
            </div>
    </footer>
</template>

<style scoped lang="scss">
@use "../styles/general.scss" as *;

footer{
    background-image: url(../assets/img/footer-bg.jpg);
    
    .container{
        display: flex;
        padding: 50px 0;
    }

        h5{
        color: white;
        padding: 20px 0;
        font-size: 16px;
        }

        ul{
        color: #646E66;
        padding-right: 20px;
        }
}
    
</style>