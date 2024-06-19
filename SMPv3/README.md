
### README for Mod Importing System for SMP Minecraft

#### Table of Contents
- [SMPv3 Setup](#smpv3-setup)
- [Transferring Data](#transferring-data)
- [Installing Mods](#installing-mods)
- [Known Issues](#known-issues)
- [Other Notes](#other-notes)
---

### SMPv3 Setup
We are using Essential instead of a server to play together. The latest version is always the higher number. For example, if there are versions 1, 2, 3, 4, and 5, then 5 is the latest version.

#### How to Set Up SMPv3
If the versions are in a folder, open the folder and download all the files inside. Place these files in the same path and extract them. Then, navigate to the folder labeled "Import This Zip." Inside, there will be another zip file. Use CurseForge's import function to install this zip.

### Transferring Data
In the previous mod folder, select the following files for transfer to the new folder:

- `options.txt`
- `XaeroWorldMap`
- `XaeroWaypoints`
- `XaeroWaypoints_...` (any files matching this pattern)
- `immersive_paintings`
- `immersive_paintings_cache`
- `essential`

Copy these files into the new folder.

### Installing Mods
To install mods using CurseForge's import function, follow these steps:

Navigate to the folder labeled "Import This Zip." Inside, locate the zip file you want to install. Use CurseForge's import function to install the selected zip file.

### Known Issues
Internal Exception: io.netty.handler.codec.DecoderException: java.lang.IlegalStateException: Server sent an impossible command tree

### Other Notes
- Backups will be archived to reduce the GitHub Repository size every 10 versions. These will be found in the ARCHIVES folder
- The import zips are split into multiple parts to reduce the file sizes as GitHub is limited on that.