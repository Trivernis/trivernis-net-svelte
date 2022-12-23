<script lang="ts">
export let src: string;
export let alt: string;
export let href: string;
</script>

<a {href}>
    <img {src} {alt} />
</a>

<style lang="scss">
  a {
    padding: 15px;
    img {
      height: 50px;
      width: auto;
    }
  }
</style>
