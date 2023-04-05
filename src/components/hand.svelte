<script>
	let src = '/media/hand.png';
</script>

<img class="floating" {src} alt="handen som pekar" />

<style lang="scss">
	img {
		position: absolute;
		width: 300px;
		right: -20px;
		bottom: 100px;
	}

	.floating {
		animation-name: floating;
		animation-duration: 3s;
		animation-iteration-count: infinite;
		animation-timing-function: ease-in-out;
		margin-left: 30px;
		margin-top: 5px;
	}

	@keyframes floating {
		from {
			transform: translate(0, 0px);
		}
		65% {
			transform: translate(10px, 15px);
		}
		to {
			transform: translate(0px, -0px);
		}
	}
</style>
