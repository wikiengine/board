<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<header class="border-b">
	<a href="/">home</a>
	<a href="/g">gg</a>
	<a href="/auth/signin">signin</a>
</header>
{@render children()}
