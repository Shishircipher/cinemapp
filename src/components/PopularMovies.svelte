<script>
    export let popular;
    console.log(popular)
</script>
<h3>
    Popular Movies
</h3>
<div class="popular-movies">
    {#each popular as movie}
    <h1> {movie.title} </h1>
    {/each}
</div>