<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main class="min-h-screen flex flex-col items-center justify-center p-4">
  <div class="flex gap-8 mb-8">
    <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
      <img src={viteLogo} class="h-24 transition-all hover:drop-shadow-[0_0_2em_#646cffaa]" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank" rel="noreferrer">
      <img src={svelteLogo} class="h-24 transition-all hover:drop-shadow-[0_0_2em_#ff3e00aa]" alt="Svelte Logo" />
    </a>
  </div>
  <h1 class="text-4xl font-bold mb-6">Vite + Svelte + Tailwind</h1>

  <div class="mb-8">
    <Counter />
  </div>

  <div class="flex gap-4 mb-8">
    <button class="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded-md">Default Button</button>
    <button class="border border-gray-300 hover:bg-gray-100 px-4 py-2 rounded-md">Outline Button</button>
    <button class="text-blue-500 hover:bg-gray-100 px-4 py-2 rounded-md">Ghost Button</button>
  </div>

  <p class="mb-4 max-w-md text-center">
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer" class="text-blue-500 hover:text-blue-700">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>

  <p class="text-gray-500 text-sm">
    Click on the Vite and Svelte logos to learn more
  </p>
</main>