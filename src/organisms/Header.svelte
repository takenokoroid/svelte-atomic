<script lang="ts">
  import Box from "../atoms/Box.svelte";
  import Icon from "../atoms/Icon.svelte";
  import IconButton from "../atoms/IconButton.svelte";
  import Img from "../atoms/Img.svelte";
  import Text from "../atoms/Text.svelte";
  import Search from "../molecules/Search.svelte";
</script>

<Box class="header">
  <Box class="header-content">
    <Icon iconProvider="material-icons header-icons" icon="menu" />
    <Img src="/assets/logo.png" alt="sample" class="header-img" />
  </Box>
  <Box class="header-content">
    <Search />
  </Box>
  <Box class="header-content">
    <Icon iconProvider="material-icons header-icons" icon="apps" />
    <Icon iconProvider="material-icons header-icons" icon="more_vert" />
    <IconButton iconProvider="material-icons" icon="account_circle">
      ログイン
    </IconButton>
  </Box>
</Box>

<style>
  :global(.header) {
    display: flex;
    justify-content: space-between;
    padding-bottom: 12px;
    border-bottom: solid 1px gray;
  }
  :global(.header-img) {
    width: 120px;
    height: 56px;
    object-fit: cover;
  }
  :global(.header-content) {
    display: flex;
    vertical-align: middle;
  }
  :global(.material-icons) {
    vertical-align: middle;
  }
  :global(.header-icons) {
    padding-top: 15px;
  }
</style>
