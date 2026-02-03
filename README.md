# Plex Inventory & Storage Management
Automated auditing tools for managing a distributed Plex media library.

## Overview
This repository contains Batch and PowerShell scripts designed to inventory media files across multiple mapped network drives (W:, X:, and Y:). It generates timestamped CSV reports for library auditing and storage planning.

## Features
- **Automated Scanning**: Recursively searches for `.mkv`, `.mp4`, and other video formats.
- **Dynamic Reporting**: Generates CSVs with file paths, sizes (in bytes), and extensions.
- **Storage Summary**: Calculates total file counts for each drive.

## Usage
1. Ensure network drives (W:, X:, Y:) are mapped to your server (Kuroiokami).
2. Run `Plex.bat`.
3. Select the specific drive or "Scan All" to generate reports in `~/Desktop/Reports`.
