# SHABBA Plugins

Free VST3 plugins for macOS (Apple Silicon), made by SHABBA. Download them from the [Releases](../../releases/latest) page or from the SHABBA Plugins site.

## Install

1. Unzip the download.
2. Drag the `.vst3` into `Macintosh HD > Library > Audio > Plug-Ins > VST3` (or the same folder inside your Home folder).
3. The plugins are not notarized by Apple, so macOS blocks them at first. Open Terminal, paste this line (with your plugin's name) and press Return:

   ```
   xattr -dr com.apple.quarantine "/Library/Audio/Plug-Ins/VST3/SHABBA Halo.vst3"
   ```

4. In Ableton Live: Preferences > Plug-ins > turn on "Use VST3 Plug-In System Folders", then press Rescan. The plugins appear under Plug-ins > SHABBA.

Each zip also contains these steps in `INSTALL.txt`.

Requires a Mac with Apple Silicon (M1 or newer) and Ableton Live 11 or 12, or any VST3 host.
