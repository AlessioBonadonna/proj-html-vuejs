<template>
    <div>
        <div class="sfondo ">
            <div class="container d-flex justify-content-between aling-item-center uu">
                <div class="col-6  text-center mt-5">
                    <img class="audible" src="../../public/img/audible-app-2x-200x209.png" alt="">
                </div>
                <div class="col-6 text-white mt-5  ">
                    <h4>TITOLO GIALLO</h4>
                    <p>DESCRIZIONE DEL TITOLO BLOD </p>
                    <p>descrizione</p>
                    <p>img img img </p>
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
    background-size: cover;
    height: 70vh;
}

.uu {
    height: 100%;
}

.audible {
    height: 100%;
    filter: blur(-0.5px);
}
</style>