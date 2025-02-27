<script lang="ts">
  import { cn } from './utils';
  
  let count: number = 0
  const increment = () => {
    count += 1
  }
</script>

<div class="flex flex-col items-center gap-2">
  <p class="text-lg font-medium">Count: {count}</p>
  <button 
    on:click={increment}
    class={cn("bg-purple-600 hover:bg-purple-700 text-white px-4 py-2 rounded-md")}
  >
    Increment
  </button>
</div>