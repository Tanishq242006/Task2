# Backup and Disaster Recovery Plan

## Objective

The purpose of this plan is to protect project files and media
assets against accidental deletion, corruption, hardware failure,
or loss of access to the primary repository.

## Storage Strategy

### 1. Primary Storage

GitHub is used for:
- Project documentation
- Project configuration
- Version history
- Small project files

### 2. Media Storage

Cloud storage is used for:
- Large video files
- Audio files
- High-resolution images
- Design files
- Other large media assets

### 3. Secondary Backup

A separate backup copy of important media assets is maintained
in another cloud storage location or offline storage.

## Backup Schedule

- Daily: Backup active project files and recently changed media.
- Weekly: Perform a complete project backup.
- Monthly: Create an archived backup of important project assets.

## Disaster Scenarios

### Accidental File Deletion

Recover the file using Git history or the cloud backup.

### Corrupted Media File

Restore the last verified copy from cloud backup.

### Repository Problem

Recover project files from the latest repository backup and
restore the required Git history.

### Hardware Failure

Access the project from the cloud backup using another device.

## Recovery Procedure

1. Identify the problem.
2. Identify the latest valid backup.
3. Restore the required files.
4. Verify file integrity.
5. Check the restored project.
6. Resume normal development.

## Backup Principle

Important media assets should have multiple copies stored in
different locations to reduce the risk of permanent data loss.

## Recovery Priority

1. Project documentation
2. Raw media
3. Edited media
4. Final media
5. Project configuration
