<template>
	<img alt="Vue logo" src="./assets/logo.png" />
	<transaction msg="Welcome to Your Vue.js App" />
</template>

<script>
import Transaction from './components/Transaction.vue';

export default {
	name: 'App',
	components: {
		Transaction
	}
};
</script>

<style lang="scss">
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
