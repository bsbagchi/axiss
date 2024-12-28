<script>
    const hero=[{img:'img1.jpeg'},{img:'img2.jpeg'}]
</script>
<div>
    {#each hero as item}
    <img src={`/src/img/${item.img}`} alt="">
    {/each}
    
</div>