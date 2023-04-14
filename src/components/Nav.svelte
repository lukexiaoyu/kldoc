<script>
    export let adds=[
        {name:'ha',link:'/'},
        {name:'ha',link:'/'},
        {name:'ha',link:'/'},
    ]
</script>
<main class="my-1 grid grid-cols-12 box">
    <div></div>
    <div></div>
{#each adds as x}
    <a class="text-center transition duration-150 hover:translate-y-1 rounded-md text-lg mx-1 p-2 hover:bg-indigo-600 hover:text-white" href="{x.link}">{x.name}</a>
{/each}
</main>
<style></style>