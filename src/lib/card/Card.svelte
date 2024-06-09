<script lang="ts">
	export let title: string | undefined = undefined;
	export let desc: string | undefined = undefined;
</script>

<div>
	<h1>{title}</h1>
	<p>{desc}</p>
	<slot />
</div>
