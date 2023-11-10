<template>
    <main>
        <JumbotronSection/>
        <ContentSection/>
        <FunctionsSection/>
    </main>
</template>

<script>
import ContentSection from './Main/ContentSection.vue';
import FunctionsSection from './Main/FunctionsSection.vue';
import JumbotronSection from "./Main/JumbotronSection.vue";
export default{
    name: 'MainApp',
    components:{
        ContentSection,
        FunctionsSection,
        JumbotronSection,
    },
}
</script>

<style lang="scss">
</style>