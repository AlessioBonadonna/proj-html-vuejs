<template>
    <div>
        <div class="sfondo ">
            <div class="container d-flex justify-content-between aling-item-center fx-mis">
                <div class="col-6  text-center mt-5">
                    <img class="audible" src="../../public/img/audible-app-2x.png" alt="">
                </div>
                <div class="col-6 text-p-c text-center  ">
                    <h2 class="text-capitalize">new audiobook </h2>
                    <p class="text-warning">NO TIME TO READ? NO PROBLEM. LISTEN TO IT </p>
                    <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit.<br> Hic unde
                        consequuntur quam quo eum?
                    </p>
                    <div class="my-5">
                        <img src="../../public/img/audible-logo.png" alt="audible">
                        <img class="mx-3" src="../../public/img/bn-logo-tall.png" alt="bn">
                        <img src="../../public/img/kindle-logo-tall.png" alt="kindle">
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
.sfondo {
    background-image: url(../../public/img/banner.jpg);

    height: 70vh;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.fx-mis {
    height: 100%;
}

.text-p-c {
    color: white;
    margin-top: 150px;
}

.audible {
    height: 100%;
    widows: 75%;
    filter: blur(-0.5px);
}
</style>