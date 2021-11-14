# Spotify app
An app that allows a user to search for songs from Spotify, add them to a playlist, and save that playlist to their Spotify account.
## TODO
- Add a proper login screen before allowing access to the site, instead of asking for authorization when using the search or 'add to spotify' links.
## Potential Jamming features to implement
- Preview sample of each track
- Only display songs not currently present in the playlist in the search results
- Add a loading screen while playlist is saving
- Update the access token logic to expire at exactly the right time, instead of setting expiration from when the user initiates their next search
- After user redirect on login, restoring the search term from before the redirect
- Ensure playlist information doesn’t get cleared if a user has to refresh their access token