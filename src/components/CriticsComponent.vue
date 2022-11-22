<template>
    <div class="container p-5 d-flex">
        <div class="col-6">
            <h3 class="text-capitalize">What the critics say</h3>
            <p class="text-uppercase text-success">testimonials from around the word</p>
            <div class="testimonial">
                <img class="testimonial-img" src="../../public/img/testimonial2-2x.jpg" alt="">
                <div class="testimonial-description text-white ">
                    <div class="mt-5">
                        <h4 class="text-capitalize">best author of his generation</h4>
                        <hr>
                        <p class="mt-2"> This book will change you prospective </p>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto pariatur illum quas maiores
                            repudiandae sed suscipit, ab quam eum. </p>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione eaque dignissimos sapiente,
                            perferendis in reprehenderit quia voluptas exercitationem consequuntur facilis, minus
                            temporibus
                            quasi dolorum molestiae.</p>
                        <div class="d-flex align-items-center">
                            <img src="../../public/img/nytimes-logo-white-xsmall.png" alt="">
                            <p class="ms-2 "><strong>Justine Kilpatrick , </strong><span
                                    class="text-success text-capitalize">The new
                                    york times</span> </p>
                        </div>
                    </div>

                </div>
            </div>
        </div>
        <div class="col-6 ms-5">
            <div class="text-end">
                <button class="btn btn-warning text-white w-50 ">Read all testimonials</button>
            </div>

            <div class=" mt-5 yellow text-center">
                <h3 class="text-capitalize"> a true Masterpiece , Bravo!</h3>
                <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, culpa.
                    Ab consectetur, aperiam
                    saepe tempore fugit quia libero veritatis cupiditate.</p>
            </div>
            <div class="autor-critics d-flex">
                <img src="../../public/img/theguardian-xsmall.png" alt="theguardian">
                <span class="mt-2 ms-2 text-secondary"><strong>Gerald Hendly , </strong> The Guardian</span>
            </div>
            <div class=" mt-5 yellow text-center">
                <h3 class="text-capitalize"> a unique view on the world </h3>
                <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, culpa.
                    Ab consectetur, aperiam
                    saepe tempore fugit quia libero veritatis cupiditate. Lorem ipsum dolor sit amet. </p>
            </div>
            <div class="autor-critics d-flex">
                <img src="../../public/img/globe-xsmall.png" alt="globe ">
                <span class="mt-2 ms-2 text-secondary"><strong>Mary Maxey, </strong> The Globe And</span>
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
    padding: 50px;
    background-color: rgba(0, 0, 0, 0.178);
    width: 100%;
    height: 100%;
    border-radius: 0 0 60px 0;
}

.yellow {
    background-color: rgb(254, 254, 227);
    padding: 50px;
}
</style>