<h1>Which selector targets the highlighted element?</h1>
<code>
	<div class="codeline">&lt;div class="grapefruit"&gt;</div>
	<div class="codeline highlighted">&nbsp;&lt;p class="mango"&gt;</div>
	<div class="codeline">&nbsp;&nbsp;text content</div>
	<div class="codeline highlighted">&nbsp;&lt;/p&gt;</div>
	<div class="codeline">&lt;/div&gt;</div>
</code>
<form class="answers">
	<button class="button" href="/reference">
		<code> .mango </code>
	</button>
	<button class="button" href="/reference">
		<code> .grape </code>
	</button>
	<button class="button" href="/reference">
		<code> .avocado </code>
	</button>
	<button class="button" href="/reference">
		<code> .coconut </code>
	</button>
</form>

<style>
	h1 {
		min-width: min-content;
		width: min(100%, 55vw);
		font-size: 1.2em;
		font-weight: normal;
	}
	code {
		display: flex;
		flex-flow: column nowrap;
	}
	.answers {
		display: flex;
		gap: 1.5em;
		flex-flow: row wrap;
		margin-block: 3em;
	}
	.codeline.highlighted {
		border-left: 0.5ch solid var(--text);
		background-color: var(--background-alt);
	}
	.codeline {
		border-left: 0.5ch solid var(--background);
		display: inline-block;
	}
</style>
