# WebM to MP4 for Premiere

A Windows desktop app that converts WebM videos to MP4 for Adobe Premiere Pro.

## Download and run

Download **WebMToMP4-Windows-v1.zip** from the [latest release](../../releases/latest), extract it, then run `WebM to MP4.exe`.

## Install FFmpeg

The app needs FFmpeg separately. The easiest method on Windows is WinGet:

1. Open **Windows Terminal** or **PowerShell**.
2. Run:

   ```powershell
   winget install --id Gyan.FFmpeg.Shared -e
   ```

3. When it finishes, close and reopen the converter. If it still cannot find FFmpeg, restart Windows and try again.

The converter can use NVIDIA NVENC when available and otherwise falls back to CPU encoding. An NVIDIA GPU is optional.

This public repository contains the packaged app download only.
