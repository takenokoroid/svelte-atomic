<script lang="ts">
  export let action: string = "";
  export let src: string = "";
  export let alt: string = "";
</script>

<button>
  {#if src}
    <img {src} {alt} />
  {/if}
  {action}
</button>

<style>
</style>
