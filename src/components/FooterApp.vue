<template>
    <footer>FOOTER</footer>
    <IconsSection/>
    <BlackSection/>
</template>

<script>
import LinksSection from './Footer/LinksSection.vue';
import IconsSection from './Footer/IconsSection.vue';
import BlackSection from './Footer/BlackSection.vue';
export default{
    name: 'HeaderApp',
    components:{
        LinksSection,
        IconsSection,
        BlackSection,
    },
}
</script>

<style lang="scss">
</style>