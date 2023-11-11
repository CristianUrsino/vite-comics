<template>
    <section class="content-section">
        <div class="container">
            <h1>CURRENT SERIES</h1>
            <div class="py-4 justify-content-between align-content-center row">
                <div class="col-6 col-md-4 col-lg-2 px-5 py-y clickable" v-for="(cardData,index) in cardsData" :key="index">
                    <CardComponent
                    :img="cardData.thumb"
                    :price="cardData.price"
                    :series="cardData.series"
                    :type="cardData.type"
                    />
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import cardsDataJson from "../../data/dc-comics.json";
import CardComponent from "./CardComponent.vue";
export default{
    name:'ContentSection',
    components:{
        CardComponent,
    },
    data(){
        return{
            cardsData: cardsDataJson,
        }
    }
}
</script>

<style lang="scss">
</style>