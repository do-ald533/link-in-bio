<script lang="ts">

	export let svg: string;
	export let link: string;
	export let name: string;
	export let backgroundColor: string;
</script>

<li style:background-color={backgroundColor}>
	<img src={svg} alt="" />
	<a href={link} style:color={'white'}>
		<p>{name}</p>
	</a>
</li>

<style lang="scss">
	li {
		display: flex;
		flex-direction: row;
		justify-content: left;
		align-items: center;
		backdrop-filter: blur(10px) saturate(160%) contrast(180%);
		border-radius: 10em;
		margin: 1.4em 0;
		box-shadow: rgb(28 34 93 / 24%) 0px 2px 8px 0px;
		img {
			padding: 0.8em;
			width: 2.7em;
			height: 2.7em;
			border-radius: 50%;
			border-width: 0.1em;
			justify-self: left;
		}
		a {
			padding: 1em;
			gap: 0.5em;
			text-decoration: none;
			margin-left: 5em;
			p {
				font-size: 1em;
				font-family: 'Times New Roman', Times, serif;
				font-weight: bold;
				border-radius: 1em;
			}
		}
	}
</style>
