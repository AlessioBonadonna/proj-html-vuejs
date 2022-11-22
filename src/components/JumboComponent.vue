<template>
    <div class="jumbo  d-flex justify-content-between align-items-center">

        <div class="container ">
            <div class="col-5">
                <h1 class="text-warning">Dawn Vaughn</h1>
                <h5 class="text-white ">Best selling author and the most influential public
                    intellectual in the
                    western
                    world right now.</h5>
                <small>- The New York Times</small>
                <div class="d-flex mt-2">
                    <div>
                        <i class="fa-solid fa-arrow-left"></i>
                    </div>
                    <div class="bg-dark">
                        <i class="fa-solid fa-arrow-right text-white "></i>
                    </div>

                </div>
            </div>
        </div>
        <!--Jumbo card left-->
        <div class="jumbo-card  bg-white col-4">
            <div class="card ">
                <div class="d-flex">
                    <img class="img-jumbo" src="../../public/img/book-widget.png" alt=" book widget">

                    <div>
                        <h3>Lates Book Relase</h3>
                        <p class="text-uppercase text-warning">D Vaughn autobiogrophy </p>
                        <small class="card-fs">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Culpa minima
                            porro
                            repudiandae nisi
                            assumenda quam tempore?</small>
                    </div>

                </div>
                <div class="btn-shop mt-3 d-flex">
                    <div class="amazon-shop">
                        <button>amazon shop</button>
                    </div>
                    <div class="apple-shop">
                        <button class="reverse">apple shop</button>
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

h5 {
    font-size: 42px;
    line-height: 50px;
}

small {
    color: gray;
}

.card {
    border: 0;
    padding: 25px
}

.img-jumbo {
    width: 180px;
    height: 180px;
    ;
}

.jumbo-card {
    padding: 10px;
    position: absolute;
    bottom: 1vh;
    right: 0;
    height: 350px;
    margin-bottom: -30px;
}

button {
    border-radius: 5px 0px 0px 5px;
    border: 1px solid #3da698;
    background-color: #3da69825;
    width: 200px;
    margin-top: 20px;

    padding: 10px
}

.reverse {
    border-radius: 0px 5px 5px 0px;
}
</style>