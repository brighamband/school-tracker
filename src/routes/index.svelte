<script>
	import Child from '../lib/child.svelte';
	let text = 'hereby';
</script>

<h1>Welcome to School Tracker</h1>
<p>Say goodbye to late work!</p>
<input type="text" bind:value={text} />
<br />
<br />
<a href="/test">Go to test</a>
<Child msg="hello from parent!" />

<style>
	h1 {
		color: blue;
	}

	input {
		background: lightgray;
		border: none;
		border-radius: 0.5rem;
		padding: 1rem;
	}
</style>
