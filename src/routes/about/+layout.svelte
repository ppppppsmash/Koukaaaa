<script>
  export let data;
</script>

<h1>about</h1>

<div class="submenu">
	{#each data.sections as section}
		<a href="/about/{section.slug}">{section.title}</a>
	{/each}
</div>

<slot></slot>