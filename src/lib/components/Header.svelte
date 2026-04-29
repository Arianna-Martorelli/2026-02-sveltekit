<script>
	import Link from "$lib/components/Link.svelte";
</script>

<header class="safe-area">
	<Link title="Itz11AM" ref="/" />

	<nav>
		<Link title="About" ref="/" />
		<Link
			title="@ari_marto"
			ref="https://www.instagram.com/ari_marto"
		/>
	</nav>
</header>

<style>
	header {
		padding-block: var(--size-6);

		display: flex;
		gap: var(--size-8);
		justify-content: space-between;
		align-items: center;
	}

	nav {
		display: flex;
		gap: var(--size-6);
		align-items: center;
	}
</style>
