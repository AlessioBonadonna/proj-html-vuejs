<template>
    <div>
        <div class="list mx-4">
            <h4 class=" text-white sarif">{{ obj.title }}</h4>
            <div>
                <ul class="p-0">
                    <li class="test-secondary" v-for="(link, index) in obj.links" :key="index">
                        <a v-html="link.text" :class="{ 'active': link.current }" class="text-seconday"></a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    data() {
        return {

        };
    },
    props: [
        'obj'
    ],

}
</script>

<style lang="scss" scoped>
li {

    list-style: none;


}

.sarif {
    font-family: 'DM Serif Display', serif;

}

a {
    color: rgb(164, 162, 162);
    text-decoration: none;
    cursor: pointer;

    &:hover {
        color: rgb(164, 162, 162);
        text-decoration: none;
    }


}
</style>