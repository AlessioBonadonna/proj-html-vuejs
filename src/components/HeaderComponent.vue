<template>

    <header class="container-fluid justify-content-between align-items-center">
        <div class="container d-flex justify-content-between align-items-center">
            <div class="logo-box">
                <img class="logo h-75" src="../../public/img/author-logo-round-small.png" alt="logo">
            </div>
            <nav class="list ">
                <ul class="d-flex">
                    <li v-for="(link, index) in links" :key="index" :class="{ 'active': link.current }">
                        <a v-html="link.text" :href="link.url" :class="{ 'active': link.current }"></a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>


</template>

<script>
import { links } from '../data/data';
export default {
    data() {
        return {
            links: links
        }
    }
}
</script>

<style lang="scss" scoped>
header {
    position: fixed;
    color: white;
    z-index: 3000;
    background-color: rgba(0, 0, 0, 0.241);
    backdrop-filter: blur(5px);
}

li {
    margin-right: 10px;
    list-style: none;

}

a {
    color: white;
    text-decoration: none;

    &:hover {
        color: orange;
        border-bottom: 1px solid orange;
    }

}

.active {
    color: orange;
    border-bottom: 1px solid orange;
}


.logo {
    width: 100px;
}
</style>