<script lang="ts">
  import Button from "./atoms/Button.svelte";
  import IconButton from "./atoms/IconButton.svelte";
  import Img from "./atoms/Img.svelte";
  import Input from "./atoms/Input.svelte";
  import Link from "./atoms/Link.svelte";
  import Text from "./atoms/Text.svelte";
  import ImgLink from "./molecules/ImgLink.svelte";
  import Thumbnail from "./organisms/Thumbnail.svelte";
</script>

<main>
  <Input />
  <Button action={"search"} />
  <IconButton className={"material-icons"} icon={"home"} />
  <Link href="https://www.youtube.com/">リンク</Link>
  <Img
    src={"https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png"}
    alt={"sample"}
  />
  <ImgLink
    href="https://www.youtube.com/"
    src={"https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png"}
    alt={"sample"}
  />
  <Text>test</Text>
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
