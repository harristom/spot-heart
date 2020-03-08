# Spot Heart

To use this skill, you need to link your Spotify account. The only permissions requested are those necessary to see the currently playing track and add it to your library. I don't see your Spotify login credentials and no user data is stored.

**Click the link below to be redirected to Spotify:**

<a id="login-link">Log in</a>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
<script src="https://unpkg.com/@ungap/url-search-params@0.1.2/min.js"></script>
<script>
  params=new URLSearchParams(location.search);
  $("#login-link").attr("href", "https://accounts.spotify.com/authorize?nosignup=true&" + params.toString());
</script>
