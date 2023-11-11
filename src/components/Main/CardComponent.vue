<template>
    <img :src="img" :alt="series + 'image'">
    <h4>{{price}}</h4>
    <h5>{{ series }}</h5>
    <h6>{{ type }}</h6>
</template>

<script>
export default{
    name:'CardComponent',
    props:{
        img:String,
        price:String,
        series:String,
        type:String
    }
}
</script>

<style lang="scss">
</style>