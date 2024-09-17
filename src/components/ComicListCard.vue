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
        <h5>{{ comicName }}</h5>
    </section>

</template>

<style scoped lang="scss">

.card-item{
    width: calc(100% / 6);
    text-align: center;
    height: 200px;

    img{
        height: 100%;
    }

    h5{
        margin-top: 15px;
    color: white;
    }
}

    
</style>