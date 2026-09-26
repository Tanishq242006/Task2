# Git LFS for Media Assets

## Purpose

Git Large File Storage (Git LFS) is used to manage large binary
media files that are not suitable for normal Git storage.

## File Types

The project uses Git LFS for:

- MP4 video files
- MOV video files
- AVI video files
- WAV audio files
- MP3 audio files
- PSD design files
- ZIP archives

## Git LFS Workflow

```text
Media File
    ↓
Git LFS
    ↓
LFS Pointer in Git
    ↓
Large File Storage
