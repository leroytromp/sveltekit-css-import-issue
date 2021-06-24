<script>
	import '@patternfly/patternfly/patternfly.min.css';
</script>

<h1 class="pf-c-title pf-m-4xl">Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<button class="pf-c-button pf-m-primary" type="button">Primary</button>

<button class="pf-c-button pf-m-control" type="button" aria-label="Copy input">
	<i class="fas fa-copy" aria-hidden="true" />
</button>

<i class="fas fa-bug" />

<p>
	The squares are supposed to be icons, and the font is not correct. Downgrading to @sveltejs/kit
	1.0.0-next.115 solves the issue and loads the icons and fonts.
</p>
