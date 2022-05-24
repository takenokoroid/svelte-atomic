<script lang="ts">
  // your script goes here

  import Box from "../atoms/Box.svelte";
  import Header from "../organisms/Header.svelte";
  import Thumbnail from "../organisms/Thumbnail.svelte";
</script>

<Header />
<Box class="top">
  <Thumbnail class="top-thumbnail" />
  <Thumbnail class="top-thumbnail" />
  <Thumbnail class="top-thumbnail" />
  <Thumbnail class="top-thumbnail" />
  <Thumbnail class="top-thumbnail" />
  <Thumbnail class="top-thumbnail" />
  <Thumbnail class="top-thumbnail" />
  <Thumbnail class="top-thumbnail" />
  <Thumbnail class="top-thumbnail" />
</Box>

<style>
  :global(.top) {
    height: 85vh;
    background-color: whitesmoke;
    padding-top: 24px;
    padding-right: 10vw;
    padding-left: 10vw;
    display: flex;
    flex-wrap: wrap;
    row-gap: 24px;
    column-gap: 24px;
    justify-content: space-between;
    align-content: flex-start;
  }
</style>
