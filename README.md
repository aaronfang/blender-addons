# Blender Add-ons

Collection of Blender add-ons maintained as independent repositories and assembled here with Git submodules.

## Add-ons

- [`8bitdo-blender-viewport`](addons/8bitdo-blender-viewport) — navigate Blender
  4.5 viewports with an 8BitDo or other XInput controller on Windows.
- [`mask-layer-manager`](addons/mask-layer-manager) — store and combine continuous sculpt mask layers.

## Clone

Clone this repository with its add-ons:

```bash
git clone --recurse-submodules https://github.com/aaronfang/blender-addons.git
```

If the main repository is already cloned:

```bash
git submodule update --init --recursive
```

Each submodule has its own history and can be developed and released independently.
