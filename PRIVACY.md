# Privacy policy

Last updated: September 22, 2026

Robin Music Playlist Sync is a personal, self-hosted tool used by its owner to update two YouTube Music playlists from ListenBrainz recommendations.

## Data used

The app requests the Google YouTube account management permission (`https://www.googleapis.com/auth/youtube`). That permission is broad, but the installed program uses it to identify the owner's playlists, read playlist items, and add or remove items in the two playlists it manages: Daily Jams and Weekly Jams. It reads ListenBrainz recommendations and sends song title and artist search queries to YouTube Music to find matches. It does not download audio.

## Storage and sharing

OAuth credentials, playlist identifiers, track metadata, sync logs, and old playlist snapshots are stored on the owner's server in files restricted to the server account. They are not stored in this public repository. Requests go to Google/YouTube and ListenBrainz to provide the sync. The app does not sell data, serve ads, or use analytics.

## Retention and control

Local records remain until the owner removes them. The owner can stop the sync, revoke the app's access in Google Account settings, and delete its local authorization and data files. Revoking access prevents future YouTube account access.

Questions about this policy can be raised through this repository's GitHub Issues page.
