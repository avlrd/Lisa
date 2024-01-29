<script setup lang="ts">
</script>

<template>
	<footer>
		<div class="wrapper">
			<span>Arthur Villard</span>
			<div class="links">
				<a href="https://github.com/avlrd/" target="_blank" rel="noopener noreferrer"><i class="iconoir-github"/></a>
			</div>
		</div>
	</footer>
</template>

<style scoped>
	footer {
		background-color: rgb(0, 173, 181);
		padding: 20px 0;
		height: 10vh;
	}

	.wrapper {
		display: flex;
		justify-content: space-between;
		align-items: center;
		margin: 0 auto;
		padding: 0 20px;
	}

	.links {
		display: flex;
		align-items: center;
	}

	a {
		text-decoration: none;
		color: rgb(34, 40, 49);
		margin-left: 20px;
	}
</style>