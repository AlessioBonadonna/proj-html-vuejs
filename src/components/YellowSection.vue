<template>

    <div class=" sono-giallo d-flex">
        <div class="container d-flex justify-content-between align-items-center ">
            <div class="p-0" v-for="(im, index) in contimg" :key="index">
                <img :src="im.img" :alt="im.text" />

            </div>
        </div>

    </div>
</template>

<script>
export default {
    data() {
        return {
            contimg: [
                {

                    img: "../../public/img/ebay-logotan-2x.png",
                    text: "ebay"
                },
                {

                    img: "../../public/img/audible-logotan-2x.png",
                    text: "audible"
                },
                {

                    img: "../../public/img/bb-logotan-2x.png",
                    text: "bb logo "
                },
                {
                    img: "../../public/img/kindlefire-logotan-2x.png",
                    text: "KindleFire"
                }

            ]
        }
    }
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
    padding: 20px;
}

.sono-giallo img {

    height: 100px;
    object-fit: contain;
    margin-left: 2%;
    margin: 0 auto;
    margin-right: 2%;
}

img {
    width: 200px;
    cursor: pointer;

    &:hover {
        filter: brightness(0) invert(0);
    }
}
</style>