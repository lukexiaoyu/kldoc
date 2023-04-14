<script>
    export let nums=[1,2,3,4,5]
    export let peo={
        name:'a',
        age:18,
        sex:'man'
    }
</script>
<main class="container mx-auto my-2 p-1  grid grid-cols-3 gap-3">
    <h1 class="box">svelte demo</h1>
    {#each nums as x}
        <div class="box">{x}</div>
    {/each}
    <h1 class="box">{peo.name}-{peo.age}-{peo.sex}</h1>
</main>
<style></style>