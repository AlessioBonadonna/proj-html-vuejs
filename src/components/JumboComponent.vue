<template>
    <div class="jumbo  d-flex justify-content-between align-items-center">

        <div class="container ">
            <div class="col-5">
                <h1 class="orange corsive ">Dawn Vaughn</h1>
                <h5 class="text-white  ">Best selling author and the most influential public
                    intellectual in the
                    western
                    world right now.</h5>
                <small>- The New York Times</small>
                <div class="d-flex mt-4">
                    <div class="bg-black arrow me-1 p-2">
                        <a href="#nogo"> <i class="fa-solid fa-arrow-left text-white"></i></a>
                    </div>
                    <div class="bg-black arrow p-2">
                        <a href="#nogo"> <i class="fa-solid fa-arrow-right text-white "></i></a>
                    </div>

                </div>
            </div>
        </div>
        <!--Card -->
        <div class="little-squares-jumbo">
            <div class=""><i class="fa-solid fa-images"></i><span>Demos</span></div>
            <div><span class=""><sup>&#36;</sup>39</span><span>On Sale</span></div>
        </div>
        <!--Jumbo card left-->
        <div class="jumbo-card  bg-white col-4">
            <div class="card ">
                <div class="d-flex">
                    <img class="img-jumbo" src="../../public/img/book-widget.png" alt=" book widget">

                    <div>
                        <h3>Lates Book Relase</h3>
                        <p class="text-uppercase orange">D Vaughn autobiogrophy </p>
                        <small class="card-fs">Donec fringilla nunc eu turpis dignissim, at euismod <br>sapien
                            tincidunt.
                            Maecenas eleifend congue cursus.</small>
                    </div>

                </div>
                <div class="btn-shop mt-3 d-flex">
                    <div class="amazon-shop text-center">
                        <button> <i class="fa-brands fa-amazon"></i> Buy on amazon </button>
                    </div>
                    <div class="apple-shop">
                        <button class="reverse"> <i class="fa-brands fa-apple"></i> Buy on AppleStore</button>
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
@import '../assets/general.scss';

.jumbo {
    background-image: url(../../public/img/footer-3.jpg);
    height: 40vw;
    position: relative;

    background-size: cover;


}

.corsive {
    font-family: 'Kristi', cursive;
}

.little-squares-jumbo {
    position: absolute;
    right: 10px;
    top: 120px;
    width: 50px;
    height: 150px;

    div {
        width: 50px;
        height: 50px;
        text-align: center;
        font-size: 10px;
        color: rgb(10, 3, 61);
        background-color: white;
        border-radius: 5px;
        margin-bottom: 5px;

        &:first-of-type {
            padding: 10px 5px;


            i {
                font-size: 20px;
            }
        }

        &:last-of-type {
            padding: 5px;

            span {
                display: inline-block;

                &:first-of-type {
                    color: green;
                    font-size: 15px;
                    font-weight: bold;
                }
            }
        }
    }

}

h1 {
    font-size: 100px;
}

h5 {
    font-size: 42px;
    line-height: 50px;
    font-family: 'DM Serif Display', serif;
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

.arrow {
    width: 40px;
    text-align: center;

}
</style>