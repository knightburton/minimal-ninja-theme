# Minimal Ninja Theme

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/hacs/integration)
[![Validate](https://github.com/knightburton/minimal-ninja-theme/actions/workflows/validate.yaml/badge.svg)](https://github.com/knightburton/minimal-ninja-theme/actions/workflows/validate.yaml)

A sleek, minimal Home Assistant theme that moves in silence.

## Table of Content
  - [Screenshots](#screenshots)
    - [Dashboard Dark](#dashboard-dark)
    - [Dashboard Light](#dashboard-light)
    - [Dashboard Mobile Dark/Light](#dashboard-mobile-darklight)
  - [Installation](#installation)
    - [HACS](#hacs)
    - [Manual](#manual)


## Screenshots

### Dashboard Dark
<img width="1953" alt="dashboard-dark" src="https://github.com/user-attachments/assets/ac067370-823d-46b9-ae72-9593559f23d6" />

### Dashboard Light
<img width="1953" alt="dashboard-light" src="https://github.com/user-attachments/assets/c39946d5-368e-4e6c-9aea-c4c143683e62" />

### Dashboard Mobile Dark/Light
<p align="center">
  <img width="430" alt="mobile-dark" src="https://github.com/user-attachments/assets/c7cc5b74-86ae-4054-86eb-e28f589b044d" />
  <img width="430" alt="mobile-light" src="https://github.com/user-attachments/assets/6fdf7dae-338b-4193-8080-dc1844ded2c7" />
</p>

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
