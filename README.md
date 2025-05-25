# Neumorphic Theme

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/hacs/integration)


> The Neumorphic Theme by Nate Lubeck

## Screenshots

### Dashboard
Dark
![Theme - Dark - Dashboard](https://github.com/user-attachments/assets/d6f96de4-8002-4f92-8f25-807c192ec8f5)
Light
![Theme - Light - Dashboard](https://github.com/user-attachments/assets/487da6a5-b0c0-4165-81e6-d10c13e7dfa4)


### Settings
Dark
![Theme - Dark - Settings](https://github.com/user-attachments/assets/47999d72-1c74-485f-81a3-8f9c912f40bd)

Light
![Theme - Light - Settings](https://github.com/user-attachments/assets/fa2c9990-c30a-4fe6-8c29-07460f5be57d)

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
2. Search for `Template`.
3. Navigate to `Neumorphic` theme.
4. Press `Install`.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/etnlbck/hacs-neumorphic-template.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/etnlbck/hacs-neumorphic-template.git
```
