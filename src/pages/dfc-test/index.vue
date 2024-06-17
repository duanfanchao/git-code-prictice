<template>
	<div class="dfc-test"></div>
</template>

<script>
export default {
	name: "dfc-test",
	components: {},
	data() {
		return {
			first: 1,
			second: 2,
			third: 3,
			fourth: 4,
			fifth: 5,
		};
	},
	computed: {},
	methods: {
		changeFirst() {},
		changeSecond() {},
	},
	created() {},
	mounted() {},
};
</script>

<style lang="less" scoped>
.dfc-test {
	height: 100%;
	width: 100%;
}
</style>