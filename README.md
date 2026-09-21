# Dansgoa låtar

A small mpv/yt-dlp playlist based on the public Spotify playlist **Dansgoa låtar**.

The playlist keeps the original track order and resolves each artist/title against YouTube at playback time.

## Requirements

- mpv
- yt-dlp

## Play

```bash
mpv --hwdec=auto \
  --ytdl-format='bestvideo[vcodec^=avc1]+bestaudio/best[vcodec^=avc1]' \
  --playlist=dansgoa.m3u
```

Shuffle:

```bash
mpv --shuffle \
  --hwdec=auto \
  --ytdl-format='bestvideo[vcodec^=avc1]+bestaudio/best[vcodec^=avc1]' \
  --playlist=dansgoa.m3u
```

The repository contains links/search references only; no audio or video files are stored here.
