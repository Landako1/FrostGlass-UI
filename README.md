# FrostGlass UI

An elegant, "Frosted Glass" inspired dashboard design for Home Assistant. FrostGlass UI leverages CSS backdrop filters and smooth gradients to create a high-quality, floating look without sacrificing readability.

**Created with ❤️ by Landako1. If you like this project, please ⭐ the repository!**

---

## 📸 Preview

| Dark Mode |
| :--- |
| ![Preview](images/Preview.png) |

---

## ✨ Features

* **Frost Effect:** Integrated transparency using `backdrop-filter` for a genuine glass aesthetic.
* **Modern Styling:** Rounded corners, soft shadows, and subtle borders.
* **Easy Configuration:** Based on `button-card` templates – configure once, reuse everywhere.
* **Reactive:** Visual status indicators with customized glow effects.

---

## ⚠️ Prerequisites

Since this design relies on trusted components, you must have the following cards installed via HACS:

* [button-card](https://github.com/custom-cards/button-card)
* [card-mod](https://github.com/thomasloven/lovelace-card-mod)

---

## 🚀 Installation

### Option 1: HACS (Recommended)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=LANDAKO1&repository=frostglass-ui&category=plugin)

*(If the badge doesn't work: Open HACS -> Three dots (top right) -> Custom repositories -> Add URL: `https://github.com/DEIN_GITHUB_USERNAME/frostglass-ui` -> Category: Lovelace)*

### Option 2: Manual Installation
1. Download `button_card_templates.yaml` from this repository.
2. Copy the file into your `/config/www/community/frostglass-ui/` folder.
3. Include it in your dashboard configuration (see below).

---

## 🛠️ Setup

To make the templates available in your dashboard, include them at the top of your dashboard configuration (in the Raw Configuration Editor):

```yaml
button_card_templates: !include /config/www/community/frostglass-ui/button_card_templates.yaml
