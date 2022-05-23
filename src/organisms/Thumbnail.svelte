<script lang="ts">
  import Box from "../atoms/Box.svelte";
  import Text from "../atoms/Text.svelte";
  import ImgLink from "../molecules/ImgLink.svelte";
</script>

<Box class="thumbnail">
  <ImgLink href="" src="assets/ffxiv_20220501.png" alt="ff14" class="image" />
  <Box class="description">
    <ImgLink href="" src="assets/Screenshot.png" alt="icon" class="icon" />
    <Box>
      <Text class="title">【FF14】エオルゼアぶらり旅</Text>
      <Text class="detail">takenokoroid</Text>
      <Text class="detail">72 回視聴・1日前</Text>
    </Box>
  </Box>
</Box>

<style>
  :global(.thumbnail) {
    background-color: gainsboro;
    width: 300px;
  }
  :global(.description) {
    display: flex;
  }
  :global(.image) {
    max-width: 300px;
  }
  :global(.icon) {
    width: 100%;
    object-fit: cover;
    object-position: 0px 0px;
    border-radius: 50%;
    margin: 8px 8px 0px 0px;
  }
  :global(a) {
    width: 20%;
  }
  :global(.title) {
    font-size: 14px;
    margin: 8px 0px 0px 0px;
    font-weight: bolder;
  }
  :global(.detail) {
    text-align: left;
    font-size: 12px;
    color: gray;
    font-weight: bold;
    padding-left: 8px;
    margin: 0;
  }
</style>
