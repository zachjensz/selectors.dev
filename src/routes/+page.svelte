<main>
	<h1>CSS Selectors are extremely powerful</h1>
	<p>
		Targeting a class is just the beginning.<br /> Learn to target elements in ways you never thought
		possible!
	</p>
	<div class="buttons">
		<a class="button" href="/reference">Selectors&nbsp;Reference</a>
		<a class="button button-primary" href="/lessons/1">Learn&nbsp;Selectors</a>
	</div>
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
	h1 {
		min-width: min-content;
		width: min(100%, 55vw);
		font-size: max(1rem, 1.5rem + 5vmin);
		font-weight: 800;
	}
	p {
		line-height: 1.4;
	}
	.buttons {
		display: flex;
		flex-flow: row wrap;
		gap: 2em;
		margin-block: 3em;
	}
	footer {
		background-color: #222;
		color: #fff;
	}
</style>
