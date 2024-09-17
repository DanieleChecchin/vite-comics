<script>
export default{
    data(){
        return{
            navLinks:[
                'CHARACTERS',
                'COMICS',
                'MOVIES',
                'TV',
                'GAMES',
                'COLLECTIBLES',
                'VIDEOS',
                'FANS',
                'NEWS',
                'SHOP'
            ]
        }
    }
}

</script>

<template>
    <header class="container">
        <img src="../assets/img/dc-logo.png" alt="Logo dc comics">
        <nav>
            <ul class="links">
                <li v-for="navItem in navLinks"> {{ navItem }} </li>
            </ul>
        </nav>
    </header>
</template>

<style scoped lang="scss">

header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;
    

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