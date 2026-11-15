# AYN Thor — OLED Water Console Themes

Four legacy Revenge/Vendetta themes (spec 2) generated from the user's uploaded high-resolution monochrome water photograph.

| Theme | File | What it changes |
| --- | --- | --- |
| Water Console OLED | `water-console-oled.json` | Recommended balanced black/silver version |
| Water Stealth OLED | `water-stealth-oled.json` | Pure black with darker intermediate surfaces |
| Water Silver OLED | `water-silver-oled.json` | Higher-contrast silver highlights |
| Console Pure OLED | `console-pure-black.json` | Same OLED principle, without any wallpaper |

## Install in Revenge
In the legacy themes URL importer, paste a **raw** URL, e.g.

`https://raw.githubusercontent.com/Escapy99/themes/main/water-console-oled.json`

Import, select, and reload if needed.

## Background caveat
The three water variants reference the original public photo via a Pexels CDN URL derived from the source image filename. Its availability in Discord/Android has **not** been tested. If it does not display, a plugin package with the photograph bundled locally is available separately in the associated ChatGPT conversation. New Revenge versions also offer Settings → Revenge → Themes → Colors → Background → Custom image, where the downloaded photo can be selected.

## Console UI scope
These JSONs change theme colour tokens and background metadata. They do **not** rearrange Discord navigation, create controller shortcuts or implement a multi-column console interface. A separate, version-specific plugin is necessary to do that.
