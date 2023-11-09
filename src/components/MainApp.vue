<template>
    <main>
        <ContentSection/>
        <FunctionsSection/>
    </main>
</template>

<script>
import ContentSection from './Main/ContentSection.vue';
import FunctionsSection from './Main/FunctionsSection.vue';
export default{
    name: 'MainApp',
    components:{
        ContentSection,
        FunctionsSection,
    },
}
</script>

<style lang="scss">
</style>