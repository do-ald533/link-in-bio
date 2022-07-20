<script lang="ts">
	import Link from "./lib/Link.svelte";
  import Header from "./lib/Header.svelte";
</script>

<main>
  <Header />
	<ul>
		<Link
			name="github"
			link="https://github.com/do-ald533"
			svg=""
		/>
    <Link
      name="linkedin"
      link="https://www.linkedin.com/in/douglas-aldred/"
      svg=""
      />
	</ul>
</main>

<style lang="scss">
	:root {
		font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
			Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
	}

	main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}

	img {
		height: 16rem;
		width: 16rem;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4rem;
		font-weight: 100;
		line-height: 1.1;
		margin: 2rem auto;
		max-width: 14rem;
	}

	p {
		max-width: 14rem;
		margin: 1rem auto;
		line-height: 1.35;
	}

	@media (min-width: 480px) {
		h1 {
			max-width: none;
		}

		p {
			max-width: none;
		}
	}
</style>
