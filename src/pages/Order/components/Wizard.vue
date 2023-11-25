<script setup lang="ts">


</script>

<template lang="pug">
ul.wizard
	li.i1 
		a(href="#")
			span Step 1 : Cart Review
	li.i2
		a(href="#")
			span Step 2 : Checkout
	li.i3 
		a(href="#")
			span Step 3 : Special Offer
	li.i4 
		a(href="#")
			span Step 4 : Confirmation
</template>

<style lang="scss" scoped>
.wizard {

	margin: 0;
	padding: 0;
	margin: 60px 0 40px 0;

	display: flex;
	flex-direction: row;
	align-items: center;
	justify-content: space-between;

	li {
		list-style: none;
		width: auto;

		display: flex;
		align-items: center;

		&:before {
			content: " ";
			width: 40px;
			height: 40px;
			background: url('../../../assets/hfpdpfhd.png') center no-repeat;
			margin-right: 20px;
		}

		&.i3 {
			&:before {
				background-image: url('../../../assets/rtsbb.png');
			}

			a {
				font-weight: bold;
			}
		}

		&.i4 {
			&:before {
				background-image: url('../../../assets/sthfpd.png');
			}
		}
	}

	a {
		color: #000000;

		font-family: Manrope;
		font-size: 20px;
		font-weight: 400;
		line-height: 22px;
		letter-spacing: 0em;

		&:hover {
			text-decoration: underline;
		}
	}
}
</style>
