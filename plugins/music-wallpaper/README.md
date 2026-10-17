# Music Wallpaper

**Version:** 2.8.0  
**Type:** Serpantinum plugin  
**Purpose:** Match desktop wallpapers to the album artwork of the currently playing music.

## Features

- Detects currently playing media through the desktop music integration.
- Searches a configured wallpaper folder for artwork-related matches.
- Includes a settings interface in Serpantinum's Plugins tab.
- Uses Serpantinum's built-in folder picker.
- Provides animated transitions into and out of plugin settings.
- Designed to follow the language selected in Serpantinum settings.

## Compatibility

This plugin was developed for a Serpantinum / Quickshell setup. The exact dependencies and supported shell revisions should be verified against the release being installed. Test changes on your own configuration before relying on them.

## Installation

Use the `install.sh` shipped with the plugin package:

```bash
chmod +x install.sh
./install.sh
serpantinumd stop && serpantinumd start
```

Run the installer from the extracted plugin directory. It is designed to update an existing installation in place; do not manually delete an older version first.

## Uninstall

Run the included `uninstall.sh` from the extracted plugin directory. Review its output and keep a backup of your configuration.

## Notes

- The plugin may need access to your local wallpaper directory.
- If the plugin or settings screen fails to load, inspect the Quickshell / Serpantinum logs before reinstalling.
- The repository's source files and package should be kept in sync when publishing future releases.

## Changelog

### 2.8.0
- Corrected the integration path for plugin localization to follow Serpantinum's own language setting.
- Added recovery logic for the settings menu after the earlier 2.7.0 integration.
- Retained the native folder picker and animated settings transitions.

