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
import { cards } from '../data/data'

export default {
    data() {
        return {
            cards: cards
        };
    },
    components: { MainTextCenter, YellowSection, PrimoComponent, CriticsComponent, EventsComponent, SecondComponent, DamonComponent, RecentComponent }
}
</script>

<style lang="scss" scoped>
.yellow {
    background-color: #FEF7E8;
    padding: 50px;
}
</style>