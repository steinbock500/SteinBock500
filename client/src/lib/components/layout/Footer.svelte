<script>
	const year = new Date().getFullYear();
</script>

<footer>
	<div class="container">
		<span>
			<a class="underline" href="https://privacy-is-not-a-crime.de" target="_blank" rel="noopener"
			>Privacy</a
			>
			
		</span>
		<span>•</span>
		<span>
			<a
				class="underline"
				href="https://github.com/steinbock500/steinbock500"
				target="_blank"
				rel="noopener">Code</a
			>
		</span>
		<span>•</span>
		<span><a href="https://philoro.ch/swiss-wildlife" target="_blank">Wildlife</a></span>
	</div>
</footer>

<style>
	/* footer {
		position: fixed;
		height: 9vh;
		background-color: var(--accent);
		color: var(--white);
		padding: var(--s-8);
		font-size: var(--font-200);
		bottom: 0px;
		left: 0px;
		right: 0px;
		margin-bottom: 0px;
	} */
	footer {
		background-color: var(--accent);
		color: var(--white);
		padding: var(--s-8);
		font-size: var(--font-200);
	}
	.container {
		display: grid;
		gap: var(--s-2);
		justify-items: center;
		justify-content: center;
		text-align: center;
	}
	@media (min-width: 768px) {
		footer {
			padding: var(--s-12);
		}
		.container {
			display: flex;
			gap: var(--s-6);
		}
	}
	@media print {
		footer {
			display: none;
		}
	}
</style>
