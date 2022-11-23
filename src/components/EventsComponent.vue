<template>
    <div class="yellow text-center">
        <div class="container">
            <div class="mb-5">
                <h2 class="text-capitalize fs-2 sarif">upcoming events</h2>
                <h5 class="orange text-uppercase fs-6"> meet the author in person </h5>
            </div>
            <!--Card-->
            <div class="card-container d-flex justify-content-between">


                <div class="card" style="width: 25rem;" v-for="(card, index) in cardt" :key="index">
                    <img class="card-img-top" :src="card.img" alt="event 05">
                    <div class="card-body">
                        <h4 class="text-capitalize changecolor">{{ card.text }}</h4>
                        <hr>
                        <p class="card-text ">{{ card.desc }}</p>
                    </div>




                </div>

            </div>

        </div>
    </div>
</template>

<script>
import { cardt } from '../data/data'
export default {
    data() {
        return {
            cardt: cardt
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../assets/general.scss';

.card {
    border: none;

}

.sarif {
    font-family: 'DM Serif Display', serif;
}

.changecolor {
    cursor: pointer;
}

.changecolor:hover {
    color: $orange;

}

.card-img-top {
    cursor: pointer;
    transition: all 0.3s ease;
}

.card-img-top:hover {
    filter: opacity(0.7);
}
</style>