<script>
    export let data;
</script>

<div>
  {#each data.names as { name }}
    <div class="font-bold text-2xl">{name}</div>
  {/each}
</div>