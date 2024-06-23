<script lang="ts">
	import * as config from '$lib/config';
</script>

<!-- Footer -->
<footer>
	<p>{config.username} &copy {new Date().getFullYear()}</p>
	<p class="socials">
		<a href="https://github.com/sagnikc395" rel="noreferrer">Github</a>
		<a href="https://twitter.com/sagnikcw" rel="noreferrer">Twitter</a>
	</p>
</footer>

<style>
	footer {
		padding-block: var(--size-7);
		border-top: 1px solid var(--border);
	}

	p {
		color: var(--text-2);
	}

	a, a:visited,a:active {
		color:inherit;
	}
	a:hover {
		color: pink;
	}
	
</style>
