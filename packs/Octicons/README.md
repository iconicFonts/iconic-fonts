# Octicons

- [**Installation**](#installation)
- [**Usage Notes**](#usage-notes)
- [**Support**](#support)

|                 |                                                                                                                                                                                 |
| :-------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Repo            | [primer/octicons](https://github.com/primer/octicons)                                                                                                                           |
| **Version**     | `v1.0.0` <sup>_Custom_</sup>                                                                                                                                                    |
| **Fonts**       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Octicons.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Octicons.woff2) |
| **Icons**       | [SVGs](https://github.com/iconicFonts/if/tree/main/packs/Octicons/svgs) <sup>_641_</sup>                                                                                        |
| **Index**       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Octicons.csv)                                                                                                         |
| **Codepoints**  | `U+E000..U+E27F` <sup>_Custom_</sup>                                                                                                                                            |
| **Fontname**    | OcticonsIF                                                                                                                                                                      |
| **Family Name** | Octicons IF                                                                                                                                                                     |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Octicons_dark.png">
  <img alt="Octicons icons preview" src="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Octicons_light.png">
</picture>

## Installation

<details>

<summary>Linux</summary>

```sh
curl -o ~/.local/share/fonts/Octicons.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Octicons.ttf
```

Refresh font cache:

```sh
fc-cache -f ~/.local/share/fonts
```

</details>

<details>

<summary>macOS</summary>

```sh
curl -o ~/Library/Fonts/Octicons.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Octicons.ttf
```

</details>

<details>

<summary>Windows</summary>

```sh
curl -o C:\Windows\Fonts\Octicons.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Octicons.ttf
```

</details>

<details>

## Usage Notes

> [!NOTE]
>
> 1. The icon pack name, originally **Font Octicons**, was changed to **Octicons**.
> 2. The suffixes of icons were adjusted from `-fill` to `-N`, where `N` represents a number, until a unique icon name was found.
>    3 **Octicons** font is standalone and has its own [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Octicons.csv), which are different from those in the [IF](https://github.com/iconicFonts/if/blob/main/indices/if.csv) font[^1].

> [!IMPORTANT]  
> The [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Octicons.csv) for the **Octicons** font remain unchanged and will not alter in the future, ensuring that you can use the font safely even when new versions are released.

## Support

If you've found this project helpful, a little love goes a long way. Give it a :star: or share it around.

[^1]: The first glyph for the **Octicons** font starts from codepoint `E000`, while for the **iPack** font, it starts from `F228D`.
