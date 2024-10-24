<script>
	import Counter from '../lib/components/Counter.svelte';
    import { counter } from '../lib/shared.svelte'
</script>

<Counter />
<br/>
<input bind:value={counter.name}>
<div>{counter.name}</div>

<style> 
    input
    {
        border: 2px solid blue;
        border-radius: 3px;
        
    }
</style>