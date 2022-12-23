<script lang="ts">
  import Icon from "./icon.svelte";

  import githubLogo from "$lib/assets/github-logo.png";
  import discordLogo from "$lib/assets/discord-logo.png";
  import mastodonLogo from "$lib/assets/mastodon-logo.png";
</script>

<div class="home-icons">
  <Icon href="https://github.com/trivernis" src={githubLogo} alt="GitHub logo"/>
  <Icon href="https://discord.gg/ZxzM2bTeXU" src={discordLogo} alt="Discord logo"/>
  <Icon href="https://social.funkyfish.cool/@trivernis" src={mastodonLogo} alt="Mastodon logo"/>
</div>

<style lang="scss">

.home-icons {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
}
</style>