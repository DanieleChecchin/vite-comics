<script>
export default{
    data(){
        return{
            
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
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <h5>SHOP</h5>
            <ul>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>
            </div>
            <div class="center-footer">
            <h5>DC</h5>
            <ul>
                <li>Terms Of Use</li>
                <li>Privacy policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Job</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>
            </div>
            <div class="right-footer">
            <h5>SITES</h5>
            <ul>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
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