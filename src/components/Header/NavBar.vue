<template>
    <ul class="d-flex flex-wrap gap-3" >
        <li v-for="(link, index) in navList" :class="[{'active ' : isActive === index}, 'd-block']" @click="addActive(index)">{{link}}</li>
    </ul>
</template>

<script>
export default{
    name:'NavBar',
    data(){
        return{
            navList:[
                'CHARACTERS',
                'COMICS',
                'MOVIES',
                'TV',
                'GAMES',
                'COLLECTIONBLES',
                'VIDEOS',
                'FANS',
                'NEWS',
                'SHOP',
            ],
            isActive: -1,
        }
    },
    methods:{
        addActive(i) {
            this.isActive = i;
        },
    },

}
</script>

<style lang="scss">
</style>