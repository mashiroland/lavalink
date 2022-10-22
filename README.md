# Lavalink
The [Lavalink](https://github.com/freyacodes/Lavalink) Docker image for Mashiro

## Usage Example


```bash
docker run -d --name lavalink \
    -e SERVER_ADDRESS=0.0.0.0 \
    mashirodev/lavalink
```

## Environment Variables

| Name                                          | Default           | Description                                             |
| --------------------------------------------- | ----------------- | ------------------------------------------------------- |
| `SERVER_PORT`                                 | `2333`            | The port Lavalink will listen on                        |
| `SERVER_ADDRESS`                              | `127.0.0.1`       | The address Lavalink will listen on                     |
| `LAVALINK_SERVER_PASSWORD`                    | `youshallnotpass` | The password Lavalink will use                          |
| `LAVALINK_SERVER_SOURCES_YOUTUBE`             | `true`            | Whether Lavalink will use YouTube as a source           |
| `LAVALINK_SERVER_SOURCES_BANDCAMP`            | `true`            | Whether Lavalink will use Bandcamp as a source          |
| `LAVALINK_SERVER_SOURCES_SOUNDCLOUD`          | `true`            | Whether Lavalink will use SoundCloud as a source        |
| `LAVALINK_SERVER_SOURCES_TWITCH`              | `true`            | Whether Lavalink will use Twitch as a source            |
| `LAVALINK_SERVER_SOURCES_VIMEO`               | `true`            | Whether Lavalink will use Vimeo as a source             |
| `LAVALINK_SERVER_SOURCES_HTTP`                | `true`            | Whether Lavalink will use HTTP as a source              |
| `LAVALINK_SERVER_SOURCES_LOCAL`               | `true`            | Whether Lavalink will use local files as a source       |
| `LAVALINK_SERVER_BUFFER_DURATION_MS`          | `400`             | The buffer duration Lavalink will use                   |
| `LAVALINK_SERVER_FRAME_BUFFER_DURATIONS_MS`   | `5000`            | The frame buffer duration Lavalink will use             |
| `LAVALINK_SERVER_TRACK_STRUCK_THRESHOLD_MS`   | `10000`           | The track stuck threshold Lavalink will use             |
| `LAVALINK_SERVER_YOUTUBE_PLAYLIST_LOAD_LIMIT` | `6`               | The YouTube playlist load limit Lavalink will use       |
| `LAVALINK_SERVER_PLAYER_UPDATE_INTERVAL`      | `5`               | The player update interval Lavalink will use            |
| `LAVALINK_SERVER_YOUTUBE_SEARCH_ENABLED`      | `true`            | Whether Lavalink will use YouTube as a search source    |
| `LAVALINK_SERVER_SOUNDCLOUD_SEARCH_ENABLED`   | `true`            | Whether Lavalink will use SoundCloud as a search source |
| `LAVALINK_SERVER_YOUTUBE_CONFIG_EMAIL`        | `null`            | The YouTube email Lavalink will use                     |
| `LAVALINK_SERVER_YOUTUBE_CONFIG_PASSWORD`     | `null`            | The YouTube password Lavalink will use                  |
| `LAVALINK_SERVER_SENTRY_DSN`                  | `null`            | The Sentry DSN Lavalink will use                        |
