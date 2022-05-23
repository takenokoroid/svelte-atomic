<script lang="ts">
  import Img from "../atoms/Img.svelte";
  import Link from "../atoms/Link.svelte";

  export let href: string = "";
  export let src: string = "";
  export let alt: string = "";
</script>

<Link {href}><Img {src} {alt} class={$$props.class} /></Link>
