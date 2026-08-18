# Mobile Forensics Using Autopsy

## Project Overview

This project demonstrates a basic practical digital forensic investigation of an Android mobile device using open-source forensic tools.

The investigation focuses on the acquisition and analysis of accessible Android evidence using Android Debug Bridge (ADB) and Autopsy. The project examines media files, metadata, EXIF information, file types, timeline activity, geolocation artifacts, communication artifacts, and trashed media.

## Objectives

- Connect an Android device to a forensic workstation using ADB.
- Acquire accessible mobile evidence through logical file acquisition.
- Preserve and document acquired evidence.
- Generate SHA-256 hashes for evidence integrity.
- Analyze acquired evidence using Autopsy.
- Examine images, videos, audio, documents, and other files.
- Investigate trashed media and metadata.
- Examine EXIF information and device attribution.
- Analyze timeline, geolocation, and communication artifacts.
- Document forensic findings and limitations.

## Device

- Device: Google Pixel 3
- Android Version: Android 12
- Acquisition Method: Logical File Acquisition
- ADB Device ID: 8CHX1PFSV

## Tools and Technologies

- Android Debug Bridge (ADB)
- Autopsy 4.23.1
- PowerShell
- SHA-256 hashing
- Windows 11

## Forensic Workflow

```text
Android Device
      |
      v
ADB Connection
      |
      v
Logical Evidence Acquisition
      |
      v
Evidence Preservation
      |
      v
SHA-256 Hashing
      |
      v
Autopsy Analysis
      |
      +---- File Types
      +---- Images & Videos
      +---- EXIF Metadata
      +---- File Metadata
      +---- Trashed Media
      +---- Timeline
      +---- Geolocation
      +---- Communications
      |
      v
Findings and Report
