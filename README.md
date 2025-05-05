# Minimal Ninja Theme

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/hacs/integration)
[![Validate](https://github.com/knightburton/minimal-ninja-theme/actions/workflows/validate.yaml/badge.svg)](https://github.com/knightburton/minimal-ninja-theme/actions/workflows/validate.yaml)

A sleek, minimal Home Assistant theme that moves in silence.

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Minimal Ninja`.
3. Navigate to `Minimal Ninja` theme.
4. Press `Download`.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/knightburton/minimal-ninja-theme.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/knightburton/minimal-ninja-theme.git
```
