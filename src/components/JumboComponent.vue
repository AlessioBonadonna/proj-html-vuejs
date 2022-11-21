<template>
    <div class="jumbo  d-flex justify-content-between align-items-center">

        <div class="container ">
            <div class="col-6">
                <h2 class="text-danger">nome</h2>
                <p class="text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam deserunt nemo
                    fugiat, velit et
                    eligendi
                    culpa mollitia veritatis illo dolores.</p>
            </div>
        </div>
        <!--Jumbo card left-->
        <div class="jumbo-card text-primary bg-white col-4">
            <div class="card ">
                <div class="d-flex">
                    <img class="img-jumbo" src="../../public/img/book-widget.png" alt=" book widget">

                    <div>
                        <h4>TITOLO GIALLO</h4>
                        <p>DESCRIZIONE DEL TITOLO BLOD </p>
                        <p>descrizione</p>
                    </div>

                </div>
                <div class="btn-shop d-flex">
                    <div class="amazon-shop">
                        <button>amazon shop</button>
                    </div>
                    <div class="apple-shop">
                        <button>apple shop</button>
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
.jumbo {
    background-image: url(../../public/img/footer-3.jpg);
    height: 40vw;
    position: relative;


}

.img-jumbo {
    width: 100px;
    height: 100px;
    ;
}

.jumbo-card {
    padding: 10px;
    position: absolute;
    bottom: 1vh;
    right: 0;
    height: 200px;
}
</style>