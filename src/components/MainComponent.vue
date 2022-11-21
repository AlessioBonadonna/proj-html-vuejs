<template>
    <main>
        <MainTextCenter />
        <YellowSection />
        <PrimoComponent />
        <CriticsComponent />
        <EventsComponent />
        <SecondComponent />
        <DamonComponent />
        <RecentComponent />

    </main>



</template>

<script>
import MainTextCenter from './MainTextCenter.vue';
import YellowSection from './YellowSection.vue';
import PrimoComponent from './PrimoComponent.vue';
import CriticsComponent from './CriticsComponent.vue';
import EventsComponent from './EventsComponent.vue';
import SecondComponent from './SecondComponent.vue';
import DamonComponent from './DamonComponent.vue';
import RecentComponent from './RecentComponent.vue';


export default {
    components: { MainTextCenter, YellowSection, PrimoComponent, CriticsComponent, EventsComponent, SecondComponent, DamonComponent, RecentComponent }
}
</script>

<style lang="scss" scoped>
.yellow {
    background-color: rgb(254, 254, 227);
    padding: 50px;
}
</style>