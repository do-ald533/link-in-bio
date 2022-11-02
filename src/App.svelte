<script lang="ts">
	import Link from "./lib/Link.svelte";
	import Header from "./lib/Header.svelte";
</script>

<main>
	<Header />
	<ul>
		<Link
			name="Github"
			link="https://github.com/do-ald533"
			svg="github.svg"
			backgroundColor="#000a"
		/>
		<Link
			name="Linkedin"
			link="https://www.linkedin.com/in/douglas-aldred/"
			svg="linkedin-logo.svg"
			backgroundColor="#0077B5"
		/>
		<Link
			name="Twitter"
			link="https://twitter.com/DAld533"
			svg="twitter.svg"
			backgroundColor="#1da1f2"
		/>
		<Link 
			name="Reddit"
			link="https://www.reddit.com/user/do-ald533"
			svg="reddit.svg"
			backgroundColor="#FF5700"
		/>
		<Link 
			name="Codewars"
			link="https://www.codewars.com/users/do-ald533"
			svg="codewars.svg"
			backgroundColor="#d43a08"
		/>
		<Link 
			name="Leetcode"
			link="https://leetcode.com/do-ald533/"
			svg="leetcode.svg"
			backgroundColor="#00bcd4"
		/>
		<Link 
			name="Medium"
			link=""
			svg="medium.svg"
			backgroundColor="#39ff14"
		/>
	</ul>
</main>


<style lang="scss">
	main {
		position: relative;
	}

	ul {
		box-sizing: border-box;
		list-style: none;
		margin: 0 auto;
		padding: 2em;
		max-width: 480px;
	}

</style>
