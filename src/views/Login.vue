<template lang="pug">
div.login
  section.section.has-text-left
    div.container
      h3.is-size-3 Let's get started
      a.button.is-primary.is-rounded.is-large(
        href="https://api.smart-lists.dwelsh.uk/login"
      ) Login with Spotify
  section.section
    div.container
      p.info
      |
      em.info Logging in with Spotify will create a Smart Playlists account for you. We store your email&nbsp;
        | so we can contact you about functional changes to your account, as well as a Spotify access token
        | that allows us to make changes to your Spotify account, essential to making smart playlists.
        | The full permissions you grant us to make changes to your account are listed
        | on the Spotify authentication page. We also store a cookie in your browser which is an
        | access token for our services. This is stored every time you login and is deleted automatically
        | by your browser after 24 hours.
      |
      br
      |
      br
      |
      strong.strong &nbsp;If you click login you agree to these conditions.
</template>

<script>
export default {
  name: 'Login',
};
</script>

<style scoped>
.info {
  color: #888888;
}

.button {
  margin-top: 5%;
}

.login {
  min-height: 50vh;
}
</style>
