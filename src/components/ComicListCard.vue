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
    
</template>

<style scoped lang="scss">
    
</style>