<script lang="ts">
import { compute_rest_props } from "svelte/internal";


  export let iconProvider: string;
  export let icon: string = "";
</script>

<button>
  <span class={iconProvider}>{icon}</span>
  <slot class={$$props.class}><!-- optional fallback --></slot>
</button>

<style>
</style>
