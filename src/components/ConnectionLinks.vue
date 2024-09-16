<script>
export default{
    data(){
        return{
            
        }
    }
}
</script>

<template>
    <section>
        <ul class="container">
            <li> <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics"><span>DIGITAL COMICS</span></li>
            <li> <img src="../assets/img/buy-comics-merchandise.png" alt="Dc Merchandise"><span>DC MERCHANDISE</span></li>
            <li> <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscription"><span>SUBSCRIPTION</span></li>
            <li> <img src="../assets/img/buy-comics-shop-locator.png" alt="Shop Locator"><span>COMIC SHOP LOCATOR</span></li>
            <li> <img src="../assets/img/buy-dc-power-visa.svg" alt="Power Visa"><span>DC POWER VISA</span></li>
        </ul>
    </section>
</template>

<style scoped lang="scss">
@use "../styles/general.scss" as *;

section{
    background-color: #0282F9;
    padding: 40px 0;

    ul{
        display: flex;
        justify-content: center;
        align-items: center;


        li{
            color: white;
            display: flex;
            align-items: center;
            padding-right: 30px;
            font-size: 14px;
            
            img{
                width: 40px;
                height: 50px;
                margin-right: 10px;
            }
            
        }
    }
    
}
    
</style>