# Amphi Flatpak Build Files

This repository contains Flatpak build manifests for Amphi applications.

## Install Apps

If you're a user and just want to install Amphi apps:

### 1. Add the Amphi Flatpak repository (if you haven't already)

```bash
flatpak remote-add --user --if-not-exists amphi https://amphi.site/amphi.flatpakrepo
```

### 2. Install Apps

#### Notes

```bash
flatpak install amphi com.amphi.notes
```

#### Music

```bash
flatpak install amphi com.amphi.music
```

## Build

If you want to build the apps locally using flatpak-builder:

### Example (Notes)

```bash
flatpak-builder --user --install --force-clean notes/build-dir notes/com.amphi.notes.yaml
```

## Issues & Contributions

If you encounter any issues or want to contribute, please open an issue or pull request in the corresponding GitHub repositories:
- [Notes](https://github.com/amphi2024/notes)
- [Music](https://github.com/amphi2024/music)