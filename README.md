# Dansgoa låtar

A small mpv/yt-dlp playlist based on the public Spotify playlist **Dansgoa låtar**.

The playlist resolves each artist/title against YouTube at playback time.

> The current M3U contains the 100 tracks extracted so far. The Spotify playlist may contain more tracks.

## Requirements

- mpv
- yt-dlp

## Play

```bash
chmod +x dansgoa
./dansgoa
```

Shuffle:

```bash
./dansgoa --shuffle
```

## Install as a command

Keep `dansgoa.m3u` with the repository and install the script:

```bash
sudo install -m 755 dansgoa /usr/local/bin/dansgoa
```

When running an installed copy, point it at the playlist:

```bash
DANSGOA_PLAYLIST="$PWD/dansgoa.m3u" dansgoa
```

The script uses the AVC1 mpv/yt-dlp format that works smoothly on the target setup.

The repository contains links/search references only; no audio or video files are stored here.
