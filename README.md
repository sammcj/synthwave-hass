# Synthwave-Hass (personal fork)

[![Version](https://img.shields.io/badge/version-0.3.8-green.svg?style=flat-square&labelColor=2a2139&color=f92aad)](#)
[![Maintained](https://img.shields.io/badge/maintained-personal%20use-f92aad.svg?style=flat-square&labelColor=2a2139)](#)

> **Heads up:** This is my personal fork of the (unmaintained) [bbbenji/synthwave-hass](https://github.com/bbbenji/synthwave-hass) theme. I update it occasionally to fix things that break for me on newer Home Assistant releases. It is **not officially supported**, comes with no guarantees, and YMMV. If it works for you, great. If it doesn't, feel free to open an issue or a PR but don't expect a fast turnaround.

---

> "Do you remember that endless summer back in '84? Cruising down the ocean highway with the top down, the wind in our hair and heads buzzing with neon dreams?"
>
> No? Well, neither do I, but with this experimental theme, we can pretend to go there.

Inspired by: [Synthwave VSCode Theme](https://github.com/robb0wen/synthwave-vscode)

---

## Installation

### Option A: HACS (custom repository)

1. In HACS, open the three-dot menu and choose **Custom repositories**.
2. Add `https://github.com/sammcj/synthwave-hass` with type **Theme**.
3. Install **Synthwave** from the HACS theme list.
4. Make sure your `configuration.yaml` includes:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```
5. Restart Home Assistant, then pick **Synthwave** under your user profile.

### Option B: Manual

1. Find your Home Assistant config directory (often `~/.homeassistant/` or `/config/`).
2. Create a `themes` directory inside it if one doesn't exist.
3. Download the theme:
   ```bash
   wget -P themes https://raw.githubusercontent.com/sammcj/synthwave-hass/master/themes/synthwave.yaml
   ```
4. Add this to `configuration.yaml`:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```
5. Restart Home Assistant, then pick **Synthwave** under your user profile.

---

## Extras

For additional styling that is not achievable with a `.yaml` theme file, you can install [synthwave-hass-extras](https://github.com/bbbenji/synthwave-hass-extras) (from the original upstream repo, not this fork).

---

## Screenshots

Here are some visuals to get a feel for the theme:

![Screenshot 1](https://i.imgur.com/DHbESc9.png)

![Screenshot 2](https://i.imgur.com/bLhZFHy.png)

![Screenshot 3](https://i.imgur.com/BcyjeJz.png)

![Screenshot 4](https://i.imgur.com/WXg2417.png)

---

## Contributions

PRs welcome but unsupported. If you find a bug or want to improve the theme, open an issue or PR on this fork. No promises on response time.
