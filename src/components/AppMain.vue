<script>
export default{
    data(){
        return{
            
        }
    }
}
</script>

<template>
    <main>
        <p class="container">--> Content goes here <--</p>
    </main>
</template>

<style scoped lang="scss">
@use "../styles/general.scss" as *;

main{
    background-color: black;
    
    p{
        color: white;
        padding: 30px 0;
        font-size: 20px;
        font-weight: bold;
    }
}
    
</style>