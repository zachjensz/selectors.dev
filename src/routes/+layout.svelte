<main>
	<slot></slot>
</main>
<footer>
	<p class="copyright">&copy; 2023 Zach Jensz</p>
</footer>

<style>
	main {
		display: grid;
		place-content: center;
		height: 100%;
		font-size: max(1rem, 1rem + 1vmin);
		color: var(--text);
		background-color: var(--background);
	}
	main,
	footer {
		padding: max(1em, 0.5em + 2vmin);
	}
	footer {
		background-color: #222;
		color: #fff;
	}
</style>

