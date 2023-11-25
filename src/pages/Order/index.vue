<script setup lang="ts">

import Wizard from "./components/Wizard.vue";

Wizard

</script>

<template lang="pug">
.page.order
	.titles
		h1 Wait ! your order in progress.
		h2 Lorem ipsum dolor sit amet, consectetur adipiscing

	Wizard

	.content
		.l
			img(src="../../assets/image 4.png")
			.testimony
				a(href="#")
					img.profile(src="../../assets/Frame 1484578045.png")
				.text “As soon as the Clarifions arrived I put one in my bedroom. This was late in the afternoon. When I went to the bedroom in the evening it smelled clean. When I went to bed I felt I could breathe better. Wonderful.”
		.r
			h2
				span.c ONE TIME ONLY&nbsp;
				span special price for 6 extra Clarifion for only&nbsp;
				span.c $14 each
				span ($84.00 total!)
			.offer
				img(src="../../assets/Frame 13.png")
			ul.list 
				li 
					| Negative Ion Technology may&nbsp;
					span help with allergens
				li 
					| Designed for&nbsp;
					span air rejuvenation
				li 
					span Perfect for every room&nbsp;
					| in all types of places.
			.save
				img(src="../../assets/Group 1000004656.png")
				| Save&nbsp;
				span 53%&nbsp;
				| and get&nbsp;
				span 6 extra Clarifision&nbsp;
				| for only&nbsp;
				span $14 Each.
			a.cta(href="#")
				span Yes - Claim my discount
			.offer2 
			a.dont(href="#") No thanks, I don’t want this.
			.guarantee 
				img(src="../../assets/image 6.png")
				div
					| If you are not completely thrilled with your Clarifion - We have a&nbsp;	
					b 30 day satisfaction guarantee.&nbsp;
					| Please refer to our return policy at the bottom of the page for more details. Happy Shopping!
</template>

<style lang="scss" scoped>
.titles {
	>h2 {
		color: #4D5254;
	}
}


.testimony {
	background: #FFFFFF;
	border-radius: 10px;

	margin-top: 24px;

	text-align: left;
	padding: 24px;

	.profile {
		width: 237px !important;
	}

	.text {
		margin-top: 16px;
	}
}

.content {
	background: #FAFAFA;
	padding: 40px;
	border-radius: 10px;

	display: flex;
	flex-direction: row;

	color: #4D5254;

	gap: 40px;

	.l {
		img {
			width: 575px;
			border-radius: 10px
		}
	}

	.r {
		width: 100%;
		text-align: left;

		h2 {
			font-size: 32px;
			font-weight: 400;
			line-height: 45px;

			.c {
				color: #2C7EF8;
			}
		}

		.offer {
			margin-top: 24px;
		}

		.list {
			color: #4D5254;
			margin: 0;
			padding: 0;

			margin: 32px 0;

			li {
				list-style: none;
				margin-bottom: 1rem;

				display: flex;
				flex-direction: row;

				&::before {
					content: " ";
					width: 22px;
					height: 22px;
					background: url('../../assets/tick-circle.png') center no-repeat;
					margin-right: 12px;
				}

				>span {
					font-weight: bold;
				}
			}
		}

		.save {
			background-color: #EDF3FD;
			padding: 12px 16px;
			border-radius: 10px;

			display: flex;
			flex-direction: row;
			align-items: center;

			img {
				margin-right: 1rem;
			}

			span {
				color: #2C7EF8;
			}
		}

		.cta {
			background: #59AE43;
			border-radius: 50px;
			padding: 16px 64px;

			display: block;

			margin-top: 32px;

			font-family: Manrope;
			font-size: 20px;
			font-weight: 700;
			line-height: 27px;
			letter-spacing: 0px;
			text-align: center;

			color: #FFFFFF;

			transition: background-color 0.15s linear;

			&:hover {
				background-color: #f15518;
			}

			span {
				display: inline-block;
				display: flex;
				align-items: center;
				justify-content: center;
			}

			span:after {
				content: " ";
				display: inline-block;
				width: 22px;
				height: 22px;
				background: url('../../assets/Line 1.png') center no-repeat;
				margin-left: 12px;

			}

		}

		.offer2 {
			margin-top: 12px;
			text-align: center;

			border: 1px solid #CFCFCF;
			border-radius: 4px;

			background: url('../../assets/Frame 1000004691.png') center no-repeat;
			height: 33px;
		}

		.dont {
			font-size: 18px;
			font-weight: 500;
			line-height: 25px;
			letter-spacing: 0px;
			text-align: center;
			color: #F82C2C;

			margin-top: 20px;
			text-transform: uppercase;
			text-decoration: underline;

			display: block;
		}

		.guarantee {
			margin-top: 32px;

			display: flex;
			flex-direction: row;
			align-items: center;

			line-height: 22.4px;

			color: #4D5254;

			img {
				margin-right: 1rem;
			}
		}
	}

}
</style>