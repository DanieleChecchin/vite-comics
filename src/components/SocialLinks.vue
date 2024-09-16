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
        <div class="container">
            <div class="left-section">
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="right-section">
                <div class="social">
                    <a href="#">FOLLOW US</a>
                    <figure>
                        <img src="../assets/img/footer-facebook.png" alt="Facebook">
                        <img src="../assets/img/footer-twitter.png" alt="Twitter">
                        <img src="../assets/img/footer-youtube.png" alt="Youtube">
                        <img src="../assets/img/footer-pinterest.png" alt="Pinterest">
                        <img src="../assets/img/footer-periscope.png" alt="Periscope">
                    </figure>
                </div>
                
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use "../styles/general.scss" as *;

section{
    background-color: #303030;
    padding: 30px 0;

    .container{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    button{
        background-color: transparent;
        color: white;
        border-color: #0282F9;
        padding: 10px 15px;
    }

    .social{
        display: flex;
        align-items: center;
    }

    a{
        color: #0282F9;
        font-weight: bold;
    }

    a,
    img{
        margin-right: 10px;
    }
}
</style>