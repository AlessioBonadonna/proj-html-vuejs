<template>
    <div class="sfondo-due">
        <div class="centrale">
            <h1 class="text-capitalize mb-4 sarif">Subscribe to my newsletter</h1>
            <p class="text-warning text-uppercase"> be notificate about book signing tour dates</p>
            <input type="email" class="input" placeholder="Insert your email ..*">
            <button class="btn btn-success ms-3 ">Subscribe</button>
            <p class="text-secondary mt-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae labore
                delectus
            </p>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.sfondo-due {
    background-image: url(../../public/img/banner-2.jpg);
    height: 70vh;
    background-size: cover;
    padding: 15vh;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;

}

.sarif {
    font-family: 'DM Serif Display', serif;
}

.centrale {
    text-align: center;
    margin: 0 auto;
    width: 450px;
    color: white;
}

.input {
    width: 200px;
    height: 40px;
    padding: 5px;

}

button {
    padding: 10px;
    width: 150px;
}
</style>