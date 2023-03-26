<script>
  	const url = "https://www.youtube.com/watch?v=";
	const videos = [
		{ video: "S4bn6gg-BmE", name: 'Messi' },
		{ video: "MD6WXsjdcsY", name: 'Ronaldo' },
		{ video: "yTGr45ZQRdA", name: 'Neymar' }
	];
</script>

<div>
	<h5>Famous soccer players:</h5>
  	<ul> 
    	{#each videos as players }
    	<li> {players.name} <span style='color: darkorchid'>{url}{players.video}</span> </li>
    	{/each}
 	</ul>	
</div>
