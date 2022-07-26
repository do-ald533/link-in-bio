<script lang="ts">

	export let svg: string;
	export let link: string;
	export let name: string;
</script>

<li>
	<a href={link}>
		<img src={svg} alt="" />
		<p>{name}</p>
	</a>
</li>

<style lang="scss">
	li {
		backdrop-filter: blur(10px) saturate(160%) contrast(180%);
		border-radius: 10em;
		margin: 1.4em 0;
		box-shadow: rgb(28 34 93 / 24%) 0px 2px 8px 0px;
		a {
			display: flex;
			flex-direction: row;
			align-items: center;
			justify-content: left;
			padding: 1em;
			gap: 0.5em;

			img {
				width: 2.5em;
				height: 2.5em;
				border-radius: 50%;
			}

			p {
				font-size: 0.8em;
				font-weight: bold;
				border-radius: 1em;
				margin-left: 5em;
			}
		}
	}
</style>
