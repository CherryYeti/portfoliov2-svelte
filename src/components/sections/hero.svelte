<div class="hero" id="hero">
	<div class="flexcontent">
		<img src="fs.png" alt="Logo" />
	</div>
	<div class="flexcontent">
		<h1>Hello, I'm</h1>
		<h1 class="herotitle">CherryYeti</h1>
	</div>
</div>

<style>
	h1 {
		color: white;
	}
	.hero {
		height: 100vh;
		width: 100%;
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-content: center;
		align-items: center;
		position: relative;
	}
	.flexcontent {
		margin: 10px;
	}
	.herotitle {
		color: #ce0e67;
		font-size: 5rem;
	}
	@media screen and (max-width: 874px) {
		.hero {
			flex-direction: column;
		}
		.herotitle {
			font-size: 4rem;
		}
		.flexcontent img {
			height: 300px;
			width: 300px;
		}
	}
</style>
