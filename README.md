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
- [Bash Inquirer Interface](https://www.github.com/tanhauhau/Inquirer.sh)
- [FFMPEG Progress Monitor](https://gist.github.com/pruperting/397509/) (Originally based on, rewritten)