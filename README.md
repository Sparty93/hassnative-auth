# hassnative-auth

The public identity page for the Hass app's Home Assistant sign-in.

Home Assistant uses IndieAuth: an app identifies itself by a URL, and Home Assistant fetches
that URL to check the app's declared redirect. `index.html` declares
`hassnative://auth-callback`. It contains no secrets.
