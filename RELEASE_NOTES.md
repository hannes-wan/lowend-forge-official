# LowEnd Forge 0.1.7

**LowEnd Forge Community Edition is free to download and use.** This release keeps the core desktop workflow available without a subscription requirement.

## What stands out in this release

- Basic Pitch onset evidence and the full CREPE monophonic pitch model work together to correct octave harmonics and recover short, high-confidence ghost notes.
- The recognition-only stem uses a true-silence timed gate, compression, excitation, and broad midrange EQ while playback keeps the untouched separated bass.
- Repeated-pitch notes split only when learned onset evidence and a real envelope reset agree, avoiding sustain fragmentation and gate-closing artifacts.
- Installers bundle the CREPE ONNX model with MIT provenance and retain the HTDemucs, Basic Pitch, and ONNX Runtime resource chain.

## Choose the right package

- **Linux x64 (APPIMAGE):** `lowend-forge-0.1.7-linux-x64.AppImage` — Portable Linux desktop package
- **Linux x64 (DEB):** `lowend-forge-0.1.7-linux-x64.deb` — Debian, Ubuntu, Mint, and compatible systems
- **Linux x64 (RPM):** `lowend-forge-0.1.7-linux-x64.rpm` — Fedora, RHEL, openSUSE, and compatible systems
- **Windows x64:** `lowend-forge-0.1.7-windows-x64-setup.exe` — Guided Windows installer

## Before you install

- Source audio, separated bass, pitch evidence, and transcription state stay on the desktop during the normal recognition path.
- Keep the installer filename and checksum together when handing a package to another machine.
- Read the [help center](https://hannes-software.com/lowend-forge/help/) for supported inputs, workflow boundaries, and troubleshooting.
- Optional licensed features are described on the website without changing the free Community Edition download.

Full product details: https://hannes-software.com/lowend-forge/
