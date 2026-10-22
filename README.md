<div align="center">

# Serpantinum Plugins

### Extensions for a desktop that feels like yours.

A growing collection of add-ons for [Serpantinum Shell](https://github.com/ilyamiro/serpantinum) — with a dedicated plugin manager, configurable extensions, and a music-aware wallpaper plugin.

<p>
  <a href="https://github.com/dimos0106-bot/SerpantinumPlugins/stargazers"><img src="https://img.shields.io/github/stars/dimos0106-bot/SerpantinumPlugins?style=flat-square&color=e5c96a&label=Stars" alt="GitHub stars"></a>
  <a href="https://github.com/dimos0106-bot/SerpantinumPlugins/network/members"><img src="https://img.shields.io/github/forks/dimos0106-bot/SerpantinumPlugins?style=flat-square&color=8c83ed&label=Forks" alt="GitHub forks"></a>
  <a href="https://github.com/dimos0106-bot/SerpantinumPlugins/commits/main"><img src="https://img.shields.io/github/last-commit/dimos0106-bot/SerpantinumPlugins?style=flat-square&color=59c9b5&label=Updated" alt="Last commit"></a>
  <img src="https://img.shields.io/badge/platform-Linux-f1d47a?style=flat-square" alt="Linux">
  <img src="https://img.shields.io/badge/shell-Serpantinum-aaa0ff?style=flat-square" alt="Serpantinum Shell">
</p>

<p>
  <a href="#-screenshots">Screenshots</a> ·
  <a href="#-plugins">Plugins</a> ·
  <a href="#-getting-started">Getting started</a> ·
  <a href="#-contributing">Contributing</a>
</p>

</div>

---

## ✦ Made for your workflow

Serpantinum Plugins is a home for small, focused extensions that fit into the desktop instead of feeling like separate apps. The goal is simple: make plugins easy to import, control, configure, and improve.

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>▦ Plugin manager</h3>
      Import `.plugin` files, see installed extensions, and enable, disable, configure, or remove them from one place.
    </td>
    <td width="33%" valign="top">
      <h3>♫ Personalisation</h3>
      Connect desktop visuals to the music you play and tune the effect to your setup.
    </td>
    <td width="33%" valign="top">
      <h3>⌘ Native integration</h3>
      Prefer Serpantinum's own settings UI, folder picker, and localisation wherever possible.
    </td>
  </tr>
</table>

## 🖼️ Screenshots

<div align="center">
  <img src="assets/Screenshot_2026-10-22-171208.png" alt="Serpantinum Plugins showing the installed Music Wallpaper extension" width="100%">
  <sub>**Plugin manager** · See installed extensions and access their controls.</sub>
</div>

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/Screenshot_2026-10-22-171212.png" alt="Music Wallpaper settings with wallpaper folder, tint strength, and current colour" width="100%">
      <p align="center"><strong>Music Wallpaper settings</strong><br><sub>Choose a folder and adjust the colour tint.</sub></p>
    </td>
    <td width="50%" valign="top">
      <img src="assets/Screenshot_2026-10-22-171150.png" alt="Empty plugin manager with the Add plugin action" width="100%">
      <p align="center"><strong>Empty state</strong><br><sub>Start by adding a `.plugin` package.</sub></p>
    </td>
  </tr>
</table>

## 🧩 Plugins

### Music Wallpaper

A Serpantinum extension that connects wallpaper colours with the artwork of the currently playing track.

- Detects the current media session.
- Searches a configured wallpaper folder for artwork-related matches.
- Includes a tint-strength control and colour preview.
- Provides settings from Serpantinum's Plugins section.
- Uses Serpantinum's native folder picker and localisation integration where available.

**Documentation:** [Music Wallpaper README](plugins/music-wallpaper/README.md)

> Check the plugin's own documentation for version details, requirements, installation steps, and known limitations.

## 🚀 Getting started

**1. Clone the repository**

```bash
git clone https://github.com/dimos0106-bot/SerpantinumPlugins.git
cd SerpantinumPlugins
```

**2. Choose an extension**

Open the relevant folder under `plugins/` and read its README before installing or changing your setup.

**3. Follow the extension-specific instructions**

Dependencies and installation procedures can differ between plugins. Keep a backup of your Serpantinum configuration before applying updates.

## 🗂️ Project structure

```text
SerpantinumPlugins/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
├── assets/
│   ├── Screenshot_2026-10-22-171150.png
│   ├── Screenshot_2026-10-22-171208.png
│   └── Screenshot_2026-10-22-171212.png
├── plugins/
│   └── music-wallpaper/
│       └── README.md
├── CONTRIBUTING.md
└── README.md
```

## 🌐 Integration principles

New extensions should stay as self-contained as practical, clearly state the Serpantinum versions and dependencies they support, and document how to install, update, and remove them. When possible, use Serpantinum's native controls and language system.

## 🤝 Contributing

Have an idea or found a bug? Use the repository's **Issues** tab. Include the plugin name, its version, your Serpantinum setup, and concise steps to reproduce the issue. Remove personal paths, tokens, and other sensitive information from logs before sharing them.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the project guidelines.

## 📜 License

No repository-wide licence has been selected yet. Unless a licence is added to the repository or to an individual plugin, do not assume redistribution or reuse is permitted.

---

<div align="center">
  <strong>Small extensions. More personal desktop.</strong><br>
  <sub>Built around Serpantinum Shell · Project in development</sub>
</div>
