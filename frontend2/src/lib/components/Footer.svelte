<div>
	<p>
		made with 🫀 by <a href="https://github.com/CSICSC" target="_blank" rel="noopener noreferrer"
			>CSI Computer Science Club</a
		>.
		<a href="https://github.com/CSICSC/CUNY-Hackathon" target="_blank" rel="noopener noreferrer"
			>⌨️ Source</a
		>.
	</p>
</div>

<style lang="scss">
	@import '$styles/variables';

	div {
		background-color: #343434;
		display: flex;
		justify-content: center;
		align-items: center;
		height: 3vh;

		p {
			color: antiquewhite;
			font-size: 20px;

			a {
				color: antiquewhite;

				&:hover {
					color: aquamarine;
				}
			}
		}
	}

	// phones (portrait)
	@media screen and (max-width: 480px) and (orientation: portrait) {
		div {
			p {
				font-size: 12px;
			}
		}
	}

	// phone (landscape)
	@media screen and (max-device-height: 480px) and (orientation: landscape) {
		div {
			p {
				font-size: 8px;
			}
		}
	}
</style>
