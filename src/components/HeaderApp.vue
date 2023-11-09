<template>
    <header> 
        <div class="container d-flex justify-content-between align-items-center flex-wrap">
            <figure class="py-2"><img src="/image/dc-logo.png" alt="logo"></figure>
            <NavBar/>
        </div>
    </header>
</template>

<script>
import NavBar from './Header/NavBar.vue';
export default{
    name: 'HeaderApp',
    components:{
        NavBar,
    },
}
</script>

<style lang="scss" scoped>
</style>