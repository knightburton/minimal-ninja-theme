# Minimal Ninja Theme

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/hacs/integration)
[![Validate](https://github.com/knightburton/minimal-ninja-theme/actions/workflows/validate.yaml/badge.svg)](https://github.com/knightburton/minimal-ninja-theme/actions/workflows/validate.yaml)

A sleek, minimal Home Assistant theme that moves in silence.

## Table of Content

- [Features](#features)
- [Screenshots](#screenshots)
  - [Dashboard Dark](#dashboard-dark)
  - [Dashboard Light](#dashboard-light)
  - [Dashboard Mobile Dark/Light](#dashboard-mobile-darklight)
- [Installation](#installation)
  - [HACS](#hacs)
  - [Manual](#manual)

## Features
- Light and Dark mode
- Minimal changes based on the default theme
- Bare contrast between the background and cards
- Tasteful amount of card shadows
- Blurred header in case of content overflow
- Integrate sidebar color
- disabled sidebar menu title bottom border
- disabled active tab underline color

## Screenshots

### Dashboard Dark

<p align="center">
  <img width="830"alt="dashboard-dark" src="https://github.com/user-attachments/assets/9563bc7b-b0eb-49f2-8f31-406f6deb6f17" />
</p>

### Dashboard Light

<p align="center">
  <img width="830" alt="dashboard-light" src="https://github.com/user-attachments/assets/801e25f9-a538-4032-8e56-3bc2dbe56ebe" />
</p>

### Dashboard Mobile Dark/Light

<p align="center">
  <img width="412" alt="mobile-dark" src="https://github.com/user-attachments/assets/9fc2a1a8-20fe-47ef-b45f-5bd5fa911498" />
  <img width="412" alt="mobile-light" src="https://github.com/user-attachments/assets/1f2da206-f942-4860-9110-ef15776312b8" />
</p>

## Prerequisites
In order to disable
- the sidebar menu title bottom border
- active tab underline color

install [card-mod](https://github.com/thomasloven/lovelace-card-mod) HACS addon as well.

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
5. (Optional) install [card-mod](https://github.com/thomasloven/lovelace-card-mod)

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
