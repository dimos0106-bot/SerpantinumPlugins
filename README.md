# Serpantinum Plugins

<p align="center">
  <strong>Small extensions. A more personal Linux desktop.</strong><br>
  A growing community-style collection of plugins and integrations for <a href="https://github.com/ilyamiro/serpantinum">Serpantinum Shell</a>.
</p>

<p align="center">
  <img alt="Platform" src="https://img.shields.io/badge/platform-Linux-7c83fd?style=for-the-badge">
  <img alt="Shell" src="https://img.shields.io/badge/shell-Serpantinum-9b72cf?style=for-the-badge">
  <img alt="Status" src="https://img.shields.io/badge/status-growing-31a875?style=for-the-badge">
</p>

---

## ✨ Plugin collection

Independent add-ons designed to make Serpantinum more useful, expressive, and customizable. Each plugin will have its own folder, installation notes, version information, and changelog where appropriate.

| Plugin | Description | Status |
|---|---|---|
| **Music Wallpaper** | Finds wallpapers that match the album artwork of the currently playing track, with music-player integration and configurable wallpaper folders. | First plugin · v1.0.0 |

> The collection is under active development. Compatibility and installation requirements will be documented for each plugin.

## 🚀 Getting started

1. Open the folder of the plugin you want to use.
2. Read that plugin's README before installing it.
3. Follow its installation and restart instructions.
4. Keep a copy of your configuration before applying updates.

**Requirements differ by plugin.** Check the individual documentation rather than assuming every extension uses the same dependencies.

## 🧩 Adding plugins

The repository is organized as a collection, not a single-plugin project:

```text
SerpantinumPlugins/
├── README.md
├── plugins/
│   ├── music-wallpaper/
│   └── <future-plugin>/
└── .gitignore
```

Each plugin should be as self-contained as possible. New additions should include:
- a concise description and screenshots where useful;
- supported Serpantinum versions and dependencies;
- installation, update, and uninstall instructions;
- a version/changelog entry;
- clear notes about known limitations.

## 🌐 Localization

Plugins may provide translations for Serpantinum's supported languages. Where possible, they should use Serpantinum's own live localization system so language changes in the shell settings are reflected automatically.

## 🤝 Contributing

Ideas, bug reports, and improvements are welcome. Before opening an issue, include the plugin name, Serpantinum version, relevant logs, and steps to reproduce the problem. Do not include personal tokens, private keys, or other secrets in logs.

## 📄 License

A repository-wide license has not been selected yet. Until one is added, do not assume that the files are licensed for redistribution or reuse. Individual plugins may specify their own license later.

---

<p align="center">
  Built for a desktop that feels like yours.
</p>
