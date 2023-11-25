<script setup lang="ts">

</script>

<template lang="pug">
ul.usps
	li.i1
		a(href="#")
			span 30-DAY SATISFACTION GUARANTEE
	li.i2
		a(href="#")
			span Free delivery on orders over $40.00
	li.i3
		a(href="#")
			span 50.000+ HAPPY CUSTOMERS
	li.i4
		a(href="#")
			span 100% Money Back Guarantee
</template>

<style lang="scss" scoped>
.usps {
	background: #252F3D;
	padding: 0;
	margin: 0;

	display: flex;
	flex-direction: row;

	li {
		font-family: 'Manrope';
		font-style: normal;
		font-weight: 500;
		font-size: 12px;
		line-height: 100%;
		list-style: none;

		margin: 0 auto;

		display: flex;
		align-items: center;

		&:before {
			content: " ";
			width: 30px;
			height: 30px;
			background: url('../assets/ic1.png') center no-repeat;
		}

		&.i2:before {
			background-image: url('../assets/ph_truck-light.png');
		}

		&.i3:before {
			background-image: url('../assets/mdi_cards-heart-outline.png');
		}

		&.i4:before {
			background-image: url('../assets/fluent_arrow-sync-checkmark-20-regular.png');
		}

		a {
			color: #FFFFFF !important;
			padding: 15px 0;

			&:hover {
				text-decoration: underline;
			}

			span {
				text-transform: uppercase;

			}
		}

	}
}
</style>
