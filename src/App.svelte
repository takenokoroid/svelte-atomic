<script lang="ts">
  import Button from "./atoms/Button.svelte";
  import IconButton from "./atoms/IconButton.svelte";
  import Img from "./atoms/Img.svelte";
  import Input from "./atoms/Input.svelte";
  import Link from "./atoms/Link.svelte";
  import Text from "./atoms/Text.svelte";
  import ImgLink from "./molecules/ImgLink.svelte";
  import Header from "./organisms/Header.svelte";
  import Thumbnail from "./organisms/Thumbnail.svelte";
</script>

<main>
  <Header />
  <Thumbnail />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
