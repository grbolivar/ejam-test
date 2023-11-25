<script setup lang="ts">


</script>

<template lang="pug">
footer
	.wrap 
		.l 
			| Copyright (c) 2023&nbsp;
			img(src="../assets/Line 2.png", alt="")
			a(href="#") clarifionsupport@clarifion.com
		.r
			img(src="../assets/lock (7) 1.png", alt="")
			| Secure 256-bit SSL encryption.
</template>

<style lang="scss" scoped>
footer {
	background-color: #252F3D;
	height: 88px;

	display: flex;
	flex-direction: row;
	align-items: center;


	color: #FFFFFF;

	a {
		color: #FFFFFF;

		&:hover {
			text-decoration: underline;
		}
	}

	.wrap {
		max-width: 1280px;
		width: 1280px;
		margin: 0 auto;

		text-align: left;

		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: left;

		>* {
			display: flex;
			flex-direction: row;
			align-items: center;
			gap: 1rem;

		}
	}

	.r {
		margin-left: auto;
	}
}
</style>
