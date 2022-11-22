<template>
    <div class="container p-5 ">
        <div class="text-center">
            <h1 class="text-capitalize">
                dig a little deeper into damon vaughun
            </h1>
            <h5 class="text-success text-capitalize">find out more the author himself</h5>


        </div>
        <div class="d-flex mt-5 text-white text-center">
            <div class="card-container d-flex justify-content-between  relat">
                <div class="card mx-5" style="width: 20rem;" v-for="(card, index ) in cards" :key="index">
                    <img class="card-img-top" :src="card.img" alt="box 1">
                    <div class="card-body">
                        <h4 class="text-capitalize mb-4">{{ card.text }} </h4>
                        <hr class="w-25 my-4">
                        <p class="card-text text-warning  mb-4">{{ card.desc }}</p>
                    </div>
                </div>
            </div>


        </div>

    </div>

</template>

<script>
import { cards } from '../data/data'
export default {
    data() {
        return {
            cards: cards,
        }
    }
}

</script>

<style lang="scss" scoped>
.card {
    border: none;
    transition: all 0.3s ease;

    &:hover {
        transform: scale(1.2);

    }
}

.relat {
    position: relative;
    border-radius: 0 0 60px 0;
}

.card-img-top {
    border-radius: 0 0 60px 0;
}



.card-body {
    position: absolute;
    bottom: 0px;
    width: 100%;

    border-radius: 0 0 60px 0;
    // background-color: rgba(0, 0, 0, 0.46);
    background: rgb(2, 0, 36);
    background: linear-gradient(0deg, rgb(5, 4, 11) 0%, rgba(20, 20, 20, 0.2) 35%, rgba(234, 234, 237, 0.01) 100%);


}

hr {
    margin: 0 auto;
}
</style>