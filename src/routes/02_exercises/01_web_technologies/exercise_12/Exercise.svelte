<script>
	let clicked = false;
</script>

<div>
	<button class="btn btn-primary" on:click={() => (clicked = true)}>
		click here
	</button>
	
	{#if clicked = false}
		<p> you have clicked the button!</p>
		{:else}
		<p> you have to click the button!</p>
	{/if}
</div>

