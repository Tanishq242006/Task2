# Cloud Storage Architecture

## Overview

The media asset management system uses GitHub for project
version control and cloud storage for large media assets
and backups.

## Architecture Components

### GitHub Repository

Used for:
- Project documentation
- Metadata
- Version control
- Project configuration

### Git LFS

Used for managing large binary media files such as:
- Videos
- Audio
- High-resolution images
- Design files

### Cloud Storage

Used for storing large media assets and maintaining
accessible copies of project files.

### Backup Storage

A secondary storage location is used to maintain backup
copies of important assets.

### Disaster Recovery

Backups can be used to restore project assets if the
primary storage or repository becomes unavailable.

## Data Flow

Media Asset
    ↓
Git / Git LFS
    ↓
Cloud Storage
    ↓
Primary Storage
    ↓
Backup Storage
    ↓
Disaster Recovery
