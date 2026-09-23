# Robin Music Playlist Sync

This is a personal, self-hosted tool that keeps two YouTube Music playlists in sync with ListenBrainz recommendations:

- **Daily Jams:** ListenBrainz Daily Jams, up to 50 tracks.
- **Weekly Jams:** ListenBrainz Weekly Jams and Weekly Exploration combined, with duplicates removed, up to 100 tracks.

The tool reads playlist data using the YouTube Data API and changes only these two managed playlists. It searches YouTube Music for matching songs; it does not download audio. It checks for new recommendations on the owner's server. This repository is the public information page for the tool. No credentials or account data are stored here.

[Privacy policy](PRIVACY.md)
