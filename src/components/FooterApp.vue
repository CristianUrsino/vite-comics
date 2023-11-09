<template>
    <footer>FOOTER</footer>
    <IconsSection/>
    <BlackSection/>
</template>

<script>
import IconsSection from './Footer/IconsSection.vue';
import BlackSection from './Footer/BlackSection.vue';
export default{
    name: 'HeaderApp',
    components:{
        IconsSection,
        BlackSection,
    },
}
</script>

<style lang="scss">
</style>