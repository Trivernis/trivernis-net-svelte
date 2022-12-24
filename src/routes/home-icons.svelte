<script lang="ts">
  import Icon from "./icon.svelte";

  import githubLogo from "$lib/assets/github-logo.png";
  import discordLogo from "$lib/assets/discord-logo.png";
  import mastodonLogo from "$lib/assets/mastodon-logo.png";
  import giteaLogo from "$lib/assets/gitea-logo.png";
  import matrixLogo from "$lib/assets/matrix-logo.png";
</script>

<div class="home-icons">
  <Icon small={true} href="https://github.com/trivernis" src={githubLogo} alt="GitHub logo"/>
  <Icon small={true} href="https://discord.gg/ZxzM2bTeXU" src={discordLogo} alt="Discord logo"/>
</div>
<div class="home-icons">
  <Icon href="https://git.trivernis.net/Trivernis" src={giteaLogo} alt="Gitea logo"/>
  <Icon href="https://social.funkyfish.cool/@trivernis" src={mastodonLogo} alt="Mastodon logo"/>
  <Icon href="https://matrix.to/#/@trivernis:trivernis.net" src={matrixLogo} alt="Matrix logo"/>
</div>

<style lang="scss">

.home-icons {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
}
</style>