# Logos

- [**Installation**](#installation)
- [**Usage Notes**](#usage-notes)
- [**Support**](#support)

| Repo            | [Lukas-W/font-logos](https://github.com/Lukas-W/font-logos)                                                                                                               |
| :-------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Version**     | `v1.0.0` <sup>_Custom_</sup>                                                                                                                                              |
| **Fonts**       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Logos.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Logos.woff2) |
| **Icons**       | [SVGs](https://github.com/iconicFonts/if/tree/main/packs/Logos/svgs) <sup>_118_</sup>                                                                                     |
| **Index**       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Logos.csv)                                                                                                      |
| **Codepoints**  | `U+E000..U+E074` <sup>_Custom_</sup>                                                                                                                                      |
| **Fontname**    | LogosIF                                                                                                                                                                   |
| **Family Name** | Logos IF                                                                                                                                                                  |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Logos_dark.png">
  <img alt="Logos icons preview" src="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Logos_light.png">
</picture>

## Installation

<details>

<summary>Linux</summary>

```sh
curl -o ~/.local/share/fonts/Logos.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Logos.ttf
```

Refresh font cache:

```sh
fc-cache -f ~/.local/share/fonts
```

</details>

<details>

<summary>macOS</summary>

```sh
curl -o ~/Library/Fonts/Logos.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Logos.ttf
```

</details>

<details>

<summary>Windows</summary>

```sh
curl -o C:\Windows\Fonts\Logos.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Logos.ttf
```

</details>

## Usage Notes

> [!NOTE]
>
> 1. The icon pack name, originally **font-ogos**, was changed to **Logos**.
> 2. The **Logos** font is standalone and has its own [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Logos.csv), which are different from those in the [IF](https://github.com/iconicFonts/if/blob/main/indices/if.csv) font[^1].

> [!IMPORTANT]
> The [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Logos.csv) for the **Logos** font remain unchanged and will not alter in the future, ensuring that you can use the font safely even when new versions are released.

## Support

If you've found this project helpful, a little love goes a long way. Give it a :star: or share it around.

[^1]: The first glyph for the **Logos** font starts from codepoint `E000`, while for the [IF](https://github.com/iconicFonts/if/blob/main/indices/if.csv) font, it starts from `F9861`.
