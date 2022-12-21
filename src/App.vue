<template>
	<div id="app"></div>
</template>

<script>
export default {
	name: "App",
	components: {},
	mounted() {
		console.log(process.env.VUE_APP_WEATHER_KEY);
	},
};
</script>

<style></style>
