<script lang="ts">
	import '../app.css';

	// src/routes/+layout.js
	export const csr = false;
	export const prerender = true;
</script>

<main class="box-border min-h-screen">
	<slot />
</main>
