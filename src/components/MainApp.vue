<template>
    <main>MAIN</main>
    <ContentSection/>
    <FunctionsSection/>
    <LinksSection/>
</template>

<script>
import ContentSection from './Main/ContentSection.vue';
import FunctionsSection from './Main/FunctionsSection.vue';
import LinksSection from './Main/LinksSection.vue';
export default{
    name: 'MainApp',
    components:{
        ContentSection,
        FunctionsSection,
        LinksSection,
    },
}
</script>

<style lang="scss">
</style>