# Video-Bulk-Downloader
Easily downloads video(s) from online streaming sources.

## Setup
1. Setup `FFmpeg`
    1. Download `ffmpeg-master-latest-win64-gpl.zip` from https://github.com/BtbN/FFmpeg-Builds/releases/tag/latest
    1. Extract the zip file to have this directory layout: `Video-Bulk-Downloader/ffmpeg-master-latest-win64-gpl/bin/ffmpeg.exe`

1. Setup `yt-dlp`
    1. Download `yt-dlp_win.zip` from https://github.com/yt-dlp/yt-dlp/releases
    1. Extract the zip file to have this directory layout: `Video-Bulk-Downloader/yt-dlp_win/yt-dlp.exe`

## Usage
1. Copy video links and paste it into `ytdl-helper-links.txt`
1. Run `ytdl-helper.bat`. This will download the videos one by one and place them in the `Downloaded` folder.
