<script>

export default {
    data() {
        return {

        }
    },
    props:{
        comicImage:{
            type: String,
            required: true,
        },
        comicPrice:{
            type: Number,
            required: false
        },
        comicName:{
            type: String,
            required: true
        },
        comicType:{
            type: String,
            required: false
        }
    }
    
}
</script>

<template>
    <section class="card-item">
        <img :src="comicImage" :alt="comicName">
        <h4>{{ comicName }}</h4>
    </section>
    
</template>

<style scoped lang="scss">

section{
    width: calc((100% / 6) - 50px / 6);

    h4{
    color: white;
    }
}


    
</style>