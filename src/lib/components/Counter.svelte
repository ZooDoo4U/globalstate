<script>
	import { counter } from '../shared.svelte';
	</script>

	<button onclick={() => counter.count += 1}>
		clicks: {counter.count}
	</button> 
<style>
	
    button
    {
		text-align: center;    
		height: 25px;          
		margin-bottom: 10px;
	} 
</style>