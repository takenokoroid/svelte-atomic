<script lang="ts">
  export let iconProvider: string;
  export let icon: string = "";
</script>

<button>
  <span class={iconProvider}>{icon}</span>
  <slot><!-- optional fallback --></slot>
</button>

<style>
</style>
