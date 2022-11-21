<template>

    <header class="container-fluid justify-content-between align-items-center">
        <div class="container d-flex justify-content-between align-items-center">
            <div class="logo-box">
                <img class="logo" src="../../public/img/author-logo-round-small.png" alt="logo">
            </div>
            <nav class="list ">
                <ul class="d-flex ">
                    <li>home</li>
                    <li>about me </li>
                    <li>Testimonial</li>
                    <li>My Blog</li>
                    <li>Meetups</li>
                    <li>Shop</li>
                    <li>Contact Me </li>
                    <li>CARRELLO</li>
                </ul>
            </nav>
        </div>
    </header>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
header {
    position: fixed;
    color: white;
    z-index: 3000;
    background-color: rgba(0, 0, 0, 0.241);
}

li {
    margin-right: 10px;
    list-style: none;
}



.logo {
    width: 100px;
}
</style>