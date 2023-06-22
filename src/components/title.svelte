<script>
    /**
	 * @type {string}
	 */
     export let text;
</script>

<div class="title">
	<h1>{text}</h1>
</div>

<style>
	.title h1 {
		color: #ce0e67;
		font-size: 5rem;
		text-align: left;
		margin-left: 10%;
		margin-bottom: 20px;
	}
	@media screen and (max-width: 874px) {
		.title h1 {
			text-align: center;
			font-size: 4rem;
			margin-left: 0%;
		}
	}
</style>
