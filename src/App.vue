<!--
  * @projectName: 
  * @desc: 
  * @author: duanfanchao
  * @date: 2024/06/20 10:00:00
-->
<template>
  <div class="app">
    <div class="header">头部</div>
    <div class="content">
        <div class="side">菜单栏</div>
        <div class="container">内容</div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'App',
    components: {},
    data () {
        return {
            data: [],
            info: null,
            num: 0,

            total: 1,
            pageSize: 20,
            pageIndex: 1,
        }
    },
    computed: {},
    methods: {
        add() {
            console.log('add');
        },
    },
    created () {},
    mounted () {},
}
</script>

<style lang="less" scoped>
.app {
    height: 100%;
    width: 100%;
}
</style>