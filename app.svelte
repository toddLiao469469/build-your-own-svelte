<script>
  let counter = 0;
  const increment = () =>  counter += 1;
  const decrement = () =>  counter -= 1;
</script>


<button on:click={increment}>Increment</button>
<div>{counter}</div>
<button on:click={decrement}>Decrement</button>
