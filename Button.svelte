<script>
	let count = 0;

	function handleClick() {
	  count += 1;
	}
</script>

<style>
	button {
	  background: #ff3e00;
	  color: aqua;
	  border: none;
	  padding: 10px 12px;
	  border-radius: 5px;
	}
</style>

<button on:click={handleClick}>
  Clicked {count} {count === 1 ? 'time' : 'times'}
</button>