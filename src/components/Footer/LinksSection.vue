<template>
    <section class="links-section">
        <div class="container d-flex py-3 d-flex justify-content-between">
            <div class="container d-flex flex-wrap">
                <ul v-for="(listLink,index) in listLinks" :key="listLink.id" >
                    <div class="me-3">
                        <li >
                            <h1>{{listLink.title}}</h1>
                        </li>
                        <li  v-for="(link, index) in listLink.links" :key="index">{{ link }}</li>
                    </div>
                </ul>
            </div>
            <figure><img src="/image/dc-logo-bg.png" alt="logo"></figure>
        </div>
    </section>
</template>

<script>
export default{
    name:'Linksection',
    data(){
        return{
            listLinks: [
                {
                    id:1,
                    title:'DC COMICS',
                    links:[
                    'characters',
                    'comics',
                    'movies',
                    'tv',
                    'games',
                    'collectionbles',
                    'videos',
                    'fans',
                    ]
                },
                {
                    id:2,
                    title:'SHOP',
                    links:[
                    'characters',
                    'comics',
                    ]
                },
                {
                    id:3,
                    title:'DC',
                    links:[
                    'characters',
                    'comics',
                    'movies',
                    'tv',
                    'games',
                    'collectionbles',
                    'videos',
                    'fans',
                    'news',
                    'shop',
                    ]
                },
                {
                    id:4,
                    title:'DC COMIC',
                    links:[
                    'characters',
                    'comics',
                    'movies',
                    'tv',
                    'games',
                    ]
                },
            ]
        }
    }
}
</script>

<style lang="scss">
</style>