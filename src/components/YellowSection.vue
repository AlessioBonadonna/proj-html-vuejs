<template>
    <div class=" sono-giallo d-flex">
        <div>
            <img src="../../public/img/ebay-logotan-2x.png" />
            <img src="../../public/img/audible-logotan-2x.png" />
            <img src="../../public/img/bb-logotan-2x.png" />
            <img src="../../public/img/kindlefire-logotan-2x.png" />
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.sono-giallo {
    margin-top: 80px;
    background-color: rgb(254, 254, 227);
    width: 100%;
    align-items: center;
}

.sono-giallo div {
    margin: 0 auto;
    text-align: center;
    padding-bottom: 20px;
}

.sono-giallo img {
    width: 20%;
    height: 100px;
    object-fit: contain;
    margin-left: 2%;
    margin: 0 auto;
    margin-right: 2%;
}

.sono-giallo img:nth-child(2) {
    filter: grayscale(2)
}
</style>