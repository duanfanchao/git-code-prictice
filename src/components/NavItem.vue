<template>
  <div class="nav-item"></div>
</template>

<script>
export default {
    name: 'nav-item',
    components: {},
    data () {
        return {
           itemList: [], 
        }
    },
    computed: {},
    methods: {},
    created () {},
    mounted () {
        console.log(this.itemList);
    },
}
</script>

<style lang="less" scoped>
.nav-item {
    width: 100%;
}
</style>