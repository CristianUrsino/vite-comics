<template>
    <section class="functions-section">
        <ul class="container d-flex justify-content-around align-items-center py-2 flex-wrap">
            <li class="d-flex mx-3 align-items-center py-3 clickable" v-for="(card,index) in cards" :key="card.id">
                <figure class="me-2 "><img :src="card.img" :alt="card.text + 'image'"></figure>
                <div>{{card.text}}</div>
            </li>
        </ul>
    </section>
</template>

<script>
export default{
    name:'FunctionsSection',
    data(){
        return{
            cards:[
                {
                    id:'1',
                    img:'/image/buy-comics-digital-comics.png',
                    text:'DIGITAL COMICS',
                },
                {
                    id:'2',
                    img:'/image/buy-comics-merchandise.png',
                    text:'DC MERCHANDISE',
                },
                {
                    id:'3',
                    img:'/image/buy-comics-subscriptions.png',
                    text:'SUBSCRIPTION',
                },
                {
                    id:'4',
                    img:'/image/buy-comics-shop-locator.png',
                    text:'COMIC SHOP LOCATOR',
                },
                {
                    id:'5',
                    img:'/image/buy-dc-power-visa.svg',
                    text:'DC POWER VISA',
                },
            ]
        }
    }
}
</script>

<style lang="scss">
</style>