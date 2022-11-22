<template>
    <div class="yellow p-5">
        <div class="container d-flex ">

            <div class="col-7">
                <h3 class="">Recent Article </h3>
                <p class="text-uppercase text-success mt-4">testimonials from around the word</p>
                <div class="tips p-5 bg-white">
                    <div class="myfilter"><img src="../../public/img/20-Tips-scaled.jpg"></div>

                    <h5 class="text-capitalize mt-5"> 20 creative tips</h5>
                    <small class="text-secondary">by admin | october 24 th , 2019 | Categories : event tips &
                        tricks</small>
                    <p class="mt-3 text-secondary">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorem
                        totam laboriosam,
                        hic veritatis
                        ut mollitia!</p>
                </div>
            </div>
            <div class="col-4">
                <div class="text-end">
                    <button class="btn btn-warning text-white  mt-3  w-50">All Articles</button>
                </div>
                <div class="p-5 bg-white ms-5 mt-5">
                    <div>
                        <img class="over" src="../../public/img/thumb-08-2x-320x202.jpg" alt="">
                        <h5 class="text-capitalize mt-4">What's on your Booklist ?</h5>
                        <small class="text-capitalize text-secondary "> October 24th , 2019 | 0 comment</small>

                        <img class="mt-5 over " src="../../public/img/thumb-13-2x-320x202.jpg" alt="">
                        <h5 class="text-capitalize mt-4">Instabul travel guide </h5>
                        <small class="text-capitalize text-secondary "> October 24th , 2019 | 0 comment</small>

                    </div>
                </div>

            </div>


        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
img {
    width: 100%;


    transition: all 0.3s ease;

    &:hover {
        filter: opacity(0.7);
        transform: scale(1.08);
    }
}
</style>