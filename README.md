# SHABBA Plugins

A collection of free SHABBA VST3 plugins for macOS on Apple silicon (M1 or newer). The first public release, v1.0.0, includes 32 plugins.

- [Browse the plugin catalog](https://plugins.shabbamusic.com)
- [Download the latest release](https://github.com/Shabbamusic/shabba-plugins/releases/latest)
- [SHABBA Music on YouTube](https://www.youtube.com/@ShabbaSounds)

## Install

1. Download the plugin ZIP you want from [Releases](https://github.com/Shabbamusic/shabba-plugins/releases/latest) and unzip it.
2. Move the .vst3 bundle into Macintosh HD > Library > Audio > Plug-Ins > VST3, or the same folder inside your Home folder.
3. The plugins are not notarized by Apple, so macOS may block them at first. Open Terminal and remove the quarantine flag for the installed plugin, replacing the example name as needed. Example: xattr -dr com.apple.quarantine "/Library/Audio/Plug-Ins/VST3/SHABBA Halo.vst3"
4. In Ableton Live, go to Preferences > Plug-ins, enable Use VST3 Plug-In System Folders, then rescan. The plugins appear under Plug-ins > SHABBA.

Each ZIP also contains these steps in INSTALL.txt. Requires a Mac with Apple silicon and a VST3-compatible host. Ableton Live 11 or 12 is documented as supported.

## Downloads and integrity

GitHub shows SHA-256 digests beside the release assets. Compare the displayed digest with your downloaded file if you need to verify it.

## Help and updates

For product information, visit [plugins.shabbamusic.com](https://plugins.shabbamusic.com). Report reproducible problems in [GitHub Issues](https://github.com/Shabbamusic/shabba-plugins/issues) and include the plugin name, macOS version, host, and steps to reproduce.

Explore [Ref2Set](https://github.com/Shabbamusic/ref2set), [ARCLINE](https://github.com/Shabbamusic/arcline), [Visualizer](https://github.com/Shabbamusic/shabba-visualizer), [Audio](https://audio.shabbamusic.com), and the [SHABBA hub](https://shabbamusic.com).

## License and source availability

This repository provides release downloads and installation instructions; it does not include the plugin source code or state a software license. Confirm redistribution terms for the plugins and any third-party components before redistributing them or describing them as open source.
