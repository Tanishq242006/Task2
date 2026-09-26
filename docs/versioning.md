# Media Asset Versioning Strategy

## Purpose

A consistent versioning system is used to track changes to
media assets and prevent accidental overwriting of previous
versions.

## File Naming Convention

Media files follow this format:

project_asset_version_date.extension

## Examples

video_intro_v01_2026-09-26.mp4
video_intro_v02_2026-09-27.mp4
video_intro_v03_2026-09-28.mp4

thumbnail_main_v01_2026-09-26.png
thumbnail_main_v02_2026-09-27.png

voiceover_intro_v01_2026-09-26.wav
voiceover_intro_v02_2026-09-27.wav

## Version Numbers

v01 = Initial version
v02 = Second version
v03 = Third version

Major approved releases can use:

v1.0
v2.0
v3.0

## Versioning Rules

1. Original raw media must not be overwritten.
2. Raw media is stored in the raw folder.
3. Edited versions are stored in the edited folder.
4. Each major change receives a new version number.
5. Final approved files are stored in the final folder.
6. Git commits are used to track changes.
7. Git LFS is used for large binary media files.

## Version Workflow

Raw Asset
    ↓
v01
    ↓
v02
    ↓
v03
    ↓
Final Approved Version
