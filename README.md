# mcugen-themes

A collection of ready-to-use theme targets for **mcugen**.

These targets are designed to be downloaded or extracted directly into  
`~/.config/mcugen/targets` and used as-is.

---

## Download

### Option 1: Download ZIP (recommended, most reliable)

**Direct download link:**  
https://github.com/MeghBadonia/mcugen-themes/archive/refs/heads/main.zip

### Install using terminal

```bash
curl -L https://github.com/MeghBadonia/mcugen-themes/archive/refs/heads/main.zip -o mcugen-themes.zip
unzip mcugen-themes.zip
mkdir -p ~/.config/mcugen
cp -r mcugen-themes-main/targets ~/.config/mcugen/
```

---

### Option 2: Manual download (GUI)

1. Open:  
   https://github.com/MeghBadonia/mcugen-themes
2. Click **Code → Download ZIP**
3. Extract the archive
4. Copy the `targets/` folder into:

```text
~/.config/mcugen/targets
```

---

## After Installation

After installing or updating themes:

- Regenerate colors using **mcugen**
- Restart affected GTK applications
- **Logging out and logging back in is recommended** to ensure all apps pick up the new colors

---

## Included Targets

- GTK 4 / libadwaita
- KDE Color Scheme

---

## Screenshots

<p align="center">
  <img src="screenshots/gtk_light.png" width="42%" />
  <img src="screenshots/gtk_dark.png" width="42%" />
  <img src="screenshots/kde_light.png" width="42%" />
  <img src="screenshots/kde_dark.png" width="42%" />
</p>

---

## Notes

- Themes follow libadwaita surface and contrast rules
- Light and dark modes are handled automatically by **mcugen**
- No hardcoded colors — everything is derived from Material color roles
