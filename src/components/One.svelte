<script>
let a='bg-blue-200'
let b='bg-green-200'
const items=[
    {id:1,class:a},
    {id:2,class:a},
    {id:3,class:a},
    {id:4,class:a},
]
</script>
<main>
    {#each items as x}
        <button  {...x} on:click={()=>{x.class=b}}>{x.id}</button>
    {/each}
    
</main>
<style></style>