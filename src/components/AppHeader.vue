<script>
export default{
    data(){
        return{

        }
    }
}

</script>

<template>
    <header class="container">
        <img src="../assets/img/dc-logo.png" alt="Logo dc comics">
        <nav>
            <ul class="links">
                <li>CHARACTERS</li>
                <li class="active">COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </header>
</template>

<style scoped lang="scss">
@use "../styles/general.scss" as *;

header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    

    .links{
        display: flex;
    }

    li{
        margin-right: 15px;
        font-weight: bold;
        padding-bottom: 20px;

        &:hover,
        &.active{
            color: #0282F9;
            border-bottom: 4px solid #0282F9;
        }
    }

 
    
} 
</style>