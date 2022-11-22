<template>
    <div class="sfondo p-5 justify-content-between align-items-center kk  ">
        <div class="container  p-5 justify-content-between align-items-center mb-5  d-flex">
            <div class=" container d-flex">
                <div class="col-3">
                    <img class="col-6" src="../../public/img/author-logo-round.png" alt="">
                </div>

                <ListFooter v-for="(item, index) in menuFooter" :key="index" :obj="item" />


            </div>
        </div>

        <p class="text-secondary text-center mt-5 text-capitalize fs-6"> &copy; copyright 2012-2020 | avanda theme by
            <span class="text-white fw-bold">Themefusion </span> | all right reserverd | power by <span
                class="text-white fw-bold">WordPress</span>
        </p>

    </div>

</template>

<script>
import ListFooter from './ListFooter.vue';
import { menuFooter } from '../data/data';

export default {
    data() {
        return {
            menuFooter: menuFooter
        };
    },
    components: { ListFooter }
}
</script>

<style lang="scss" >
.sfondo {
    background-image: url(../../public/img/footer-3.jpg);
    // height: 60vh;
    ;
}




li {
    color: rgb(164, 162, 162);
}
</style>