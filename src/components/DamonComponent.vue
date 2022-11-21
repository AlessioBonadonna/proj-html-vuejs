<template>
    <div class="container p-5 ">
        <div class="text-center">
            <h1 class="text-capitalize">
                dig a little deeper into damon vaughun
            </h1>
            <h5 class="text-success text-capitalize">find out more the author himself</h5>


        </div>
        <div class="d-flex mt-5 text-white text-center">
            <div class="card-container d-flex justify-content-between relat">
                <div class="card" style="width: 25rem;">
                    <img class="card-img-top" src="../../public/img/box-1.jpg" alt="box 1">
                    <div class="card-body">
                        <h4 class="text-capitalize mb-4">about me </h4>
                        <hr class="w-25 my-4">
                        <p class="card-text text-warning  mb-4">Lorem ipsum dolor sit.</p>
                    </div>
                </div>
            </div>
            <div class="card-container d-flex justify-content-between  mx-3 relat">
                <div class="card" style="width: 25rem;">
                    <img class="card-img-top" src="../../public/img/box-4.jpg" alt="box 4 ">
                    <div class="card-body">
                        <h4 class="text-capitalize mb-4">My lastest book</h4>
                        <hr class="w-25 my-4">
                        <p class="card-text text-warning mb-4 ">Lorem ipsum dolor sit.</p>
                    </div>
                </div>
            </div>
            <div class="card-container d-flex justify-content-between relat">
                <div class="card" style="width: 25rem;">
                    <img class="card-img-top" src="../../public/img/box-3.jpg" alt="box 3">
                    <div class="card-body">
                        <h4 class="text-capitalize mb-4">book signing</h4>
                        <hr class="w-25 my-4">
                        <p class="card-text text-warning mb-4 ">Lorem ipsum dolor sit.</p>
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
.card {
    border: none;
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