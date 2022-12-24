<script lang="ts">
	export let name: string;
	export let href: string;
	export let description: string;
</script>

<div class="project">
	<div>
		<a {href}><h2>{name}</h2></a>
	</div>
	<p>{description}</p>
</div>

<style lang="scss">
	.project {
		display: flex;
		flex-direction: column;
		margin-top: 1em;
		width: 100%;
		a {
			display: inline;
			color: white;
			h2 {
				display: inline;
			}
		}
	}
</style>
