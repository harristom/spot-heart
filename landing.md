# Spot Heart

> Like the song currently playing on Spotify with Alexa

To use this skill, you must log in with the following third-party (3P) services:
* Spotify

**Click below to log in to Spotify:**

<a id="login-link">Log in</a>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
<script src="https://unpkg.com/@ungap/url-search-params@0.1.2/min.js"></script>
<script>
  params=new URLSearchParams(location.search);
  $("#login-link").attr("href", "https://accounts.spotify.com/authorize?nosignup=true&" + params.toString());
</script>
