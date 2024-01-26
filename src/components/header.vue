<script setup lang="ts">
	import { RouterLink } from 'vue-router'
</script>

<template>
	<header>
		<div class="wrapper">
			<span class="header_app_name">Lisa</span>
			<nav>
				<RouterLink to="/">Home</RouterLink>
				<RouterLink to="/about">About</RouterLink>
			</nav>
		</div>
	</header>
</template>

<style scoped>
	header {
		background-color: rgb(34, 40, 49);
		color: rgb(238, 238, 238);
		box-shadow: 0 0 1rem rgba(0, 0, 0, 0.75);
		height: 10vh;
	}

	.wrapper {
		display: flex;
		justify-content: space-around;
		align-items: center;
		height: 100%;
		margin: 0 2rem;
	}

	.header_app_name {
		font-size: 2rem;
		font-weight: 900;
	}

	nav {
		display: flex;
		height: 100%;
	}

	nav a {
		display: flex;
		align-items: center;
		text-decoration: none;
		color: inherit;
		height: 100%;
		padding: 0 1rem;
	}

	nav a:hover {
		color: rgb(0, 0, 0);
		background-color: rgb(238, 238, 238);
	}
</style>