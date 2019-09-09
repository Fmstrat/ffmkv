# ffmkv

A bash wrapper for FFMPEG with an Inquirer menu interface and progress monitoring.

<img src="screenshots/demo.gif">

## Features
- Selectable video and audio streams
- Selectable transcoding or stream copy for audio and video
- Can transcode to a specified file size or size per hour of video
- Supports x265
- Retains HDR
- Retains subtitles
- Retains original resolution
- Can build a sample video based on the specified number of seconds

## Usage

```
ffmkv <input> <output>
```

## Credits
- [Bash Inquirer Interface](https://raw.githubusercontent.com/tanhauhau/Inquirer.sh)
- [FFMPEG Progress Monitor](https://gist.githubusercontent.com/pruperting/397509/raw/7f9e2335189a3baa0255cd562853d382f3624201/ffmpeg-progress.sh) (Originally based on, rewritten)