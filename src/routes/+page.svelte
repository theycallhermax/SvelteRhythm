<svelte:head>
    <title>SvelteRhythm</title>
</svelte:head>

<div class="m-3">
    {#each new Array(20) as a}
        <div class="p-5 mb-3 bg-violet-400 rounded">
            <h1 class="text-xl font-bold">Lorem ispum dolor sit amet</h1>
            <p class="text-lg">Lorem ispum</p>
        </div>
    {/each}
</div>
