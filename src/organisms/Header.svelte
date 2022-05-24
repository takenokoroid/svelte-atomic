<script lang="ts">
  import Box from "../atoms/Box.svelte";
  import Icon from "../atoms/Icon.svelte";
  import IconButton from "../atoms/IconButton.svelte";
  import Img from "../atoms/Img.svelte";
import Text from "../atoms/Text.svelte";
  import Search from "../molecules/Search.svelte";
</script>

<Box>
  <Icon iconProvider="material-icons" icon="menu" />
  <Img src="/assets/logo.png" alt="sample"/>
  <Search />
  <Icon iconProvider="material-icons" icon="apps" />
  <Icon iconProvider="material-icons" icon="more_vert" />
  <IconButton iconProvider="material-icons" icon="account_circle"
    ><Text class="title">ログイン</Text></IconButton
  >
</Box>

<style>

</style>
