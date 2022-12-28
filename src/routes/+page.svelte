<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<div>
	<h2>Image with "" as src</h2>
	<img src="" on:error={(event) => console.log('empty src', event)} />
</div>

<div>
	<h2>Image with "nothing" as src</h2>
	<img src="nothing" on:error={(event) => console.log('nothing src')} />
</div>

<div>
	<h2>Image with "https://svelte-image-bug.net/123" as src</h2>
	<img
		src="https://svelte-image-bug.net/123"
		on:error={(event) => console.log('https://svelte-image-bug.net/123 src')}
	/>
</div>
