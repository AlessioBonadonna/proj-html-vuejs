<template>
    <div class="container p-5 d-flex">
        <div class="col-6">
            <h3>What the critics say</h3>
            <p>blablabla qualcosa </p>
            <div class="testimonial">
                <img class="testimonial-img" src="../../public/img/testimonial2-2x.jpg" alt="">
                <div class="testimonial-description text-white">
                    bla bla bla
                </div>
            </div>
        </div>
        <div class="col-6 ms-5">
            <button class="text-end">bla</button>
            <div class=" mt-5 yellow text-center">
                <h3>titolo</h3>
                <p>blablabla</p>
            </div>
            <div class="autor-critics">
                blablaqualcosa
            </div>
            <div class=" mt-5 yellow text-center">
                <h3>titolo</h3>
                <p>blablabla</p>
            </div>
            <div class="autor-critics">
                blablaqualcosa
            </div>
        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.testimonial {
    position: relative;
}

.testimonial-img {
    width: 100%;
    border-radius: 0 0 60px 0;

}

.testimonial-description {
    position: absolute;
    top: 0;
    left: 0;
    z-index: 2000;
    padding: 20px;
    background-color: rgba(0, 0, 0, 0.178);
    width: 100%;
    height: 100%;
    border-radius: 0 0 60px 0;
}

.yellow {
    background-color: lightgoldenrodyellow;
}
</style>