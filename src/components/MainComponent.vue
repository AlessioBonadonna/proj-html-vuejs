<template>
    <main>
        <MainTextCenter />
        <YellowSection />
        <PrimoComponent />
        <CriticsComponent />

    </main>



</template>

<script>
import MainTextCenter from './MainTextCenter.vue';
import YellowSection from './YellowSection.vue';
import PrimoComponent from './PrimoComponent.vue';
import CriticsComponent from './CriticsComponent.vue'

export default {
    components: { MainTextCenter, YellowSection, PrimoComponent, CriticsComponent }
}
</script>

<style lang="scss" scoped>

</style>