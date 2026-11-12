# WebM to MP4 for Premiere

A Windows desktop app that converts WebM videos to MP4 for Adobe Premiere Pro.

## Download and run

Download **WebMToMP4-Windows-v1.zip** from the [latest release](../../releases/latest), extract the ZIP, and keep the extracted folder together. Run `WebM to MP4.exe` from inside that folder.

FFmpeg is included in the ZIP. You do not need to install Python or FFmpeg separately. The download is about 124 MB.

The converter can use NVIDIA NVENC when available and otherwise falls back to Windows Media Foundation CPU encoding. An NVIDIA GPU is optional. For best results, use a current NVIDIA driver.

## What is included

- Multi-file conversion queue and drag and drop
- Remembers the last input and export folders
- Converts WebM to H.264/AAC MP4 for Premiere Pro
- FFmpeg and FFprobe bundled under `ffmpeg\bin`

The ZIP contains the packaged app, not the Python application source. See `THIRD-PARTY-NOTICES.txt` in the extracted folder for FFmpeg licensing and source links.
