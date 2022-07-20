<script lang="ts">
	export let svg: string;
	export let link: string;
	export let name: string;
</script>

<li>
	<a href={link}>
		<img src={svg} alt="" />
		{name}
	</a>
</li>

<style lang="scss">
</style>
