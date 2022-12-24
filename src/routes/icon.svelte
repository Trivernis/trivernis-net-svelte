<script lang="ts">
export let src: string;
export let alt: string;
export let href: string;
export let small = false;
</script>

<a {href} class="{small? 'small' : ''}">
    <img {src} {alt} />
</a>

<style lang="scss">
  a {
    padding: 20px;
    img {
      height: 60px;
      width: auto;
    }
  }
  a.small {
    padding: 15px;

    img {
        height: 35px;
    }
  }
</style>
