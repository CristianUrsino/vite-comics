<template>
    <section class="icons-section">
        <div class="container d-flex justify-content-between align-items-center py-3 flex-wrap">
            <button class="my-btn"><h1>SING-UP NOW</h1></button>
            <div>
                <ul class="d-flex gap-4 text-secondary py-2 flex-wrap">
                    <li><h1 class="blue-text">FOLLOW US</h1></li>
                    <li v-for="(icon,index) in icons" :key="index"><img :src="icon.img" :alt="icon.text"></li>
                </ul>
            </div>
        </div>
    </section>
</template>

<script>
export default{
    name:'IconsSection',
    data(){
        return{
            icons:[
                {
                    img:'/image/footer-facebook.png',
                    text:'facebook icon'
                },
                {
                    img:'/image/footer-twitter.png',
                    text:'twitter icon'
                },
                {
                    img:'/image/footer-youtube.png',
                    text:'youtube icon'
                },
                {
                    img:'/image/footer-pinterest.png',
                    text:'pinterest icon'
                },
                {
                    img:'/image/footer-periscope.png',
                    text:'periscope icon'
                },
            ]
        }
    }
}
</script>

<style lang="scss">
</style>