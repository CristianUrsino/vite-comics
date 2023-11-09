<template>
    <footer>
        <LinksSection/>
        <IconsSection/>
    </footer>
    
</template>

<script>
import LinksSection from './Footer/LinksSection.vue';
import IconsSection from './Footer/IconsSection.vue';
export default{
    name: 'HeaderApp',
    components:{
        LinksSection,
        IconsSection,
    },
}
</script>

<style lang="scss">
</style>