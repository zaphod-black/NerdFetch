# Changelog

All notable changes to NerdFetch-ZBRemix will be documented in this file.

## [Unreleased]

### Added
- Disk usage display showing used/free GB for all mounted drives
- Disk icons for all font options (Nerdfonts, Phosphor, Cozette, Emoji)
- "no vram" message displayed when integrated graphics have no dedicated VRAM
- Smart filtering to show only unique physical drives (avoids duplicate bind mounts)

### Changed
- Disk information displays inline with system info, above the color bar
- VRAM line now shows "no vram" instead of being blank for integrated graphics

## Previous Features

- GPU detection with VRAM usage and percentage
- CPU, Shell, Window Manager, and Terminal detection
- Memory display in GiB instead of MiB
- Custom MC cube ASCII art in teal with bright purple "MC" signature
- Fixed ANSI color code rendering
