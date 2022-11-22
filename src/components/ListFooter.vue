<template>
    <div>
        <div class="list mx-4">
            <h4 class=" text-white">{{ obj.title }}</h4>
            <div>
                <ul class="p-0">
                    <li class="test-secondary" v-for="(link, index) in obj.links" :key="index">
                        <a v-html="link.text"></a>
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
</style>