# Ionicons

- [**Installation**](#installation)
- [**Usage Notes**](#usage-notes)
- [**Support**](#support)

|                 |                                                                                                                                                                                 |
| :-------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Repo            | [ionic-team/Ionicons](https://github.com/ionic-team/Ionicons)                                                                                                                   |
| **Version**     | `v1.0.0` <sup>_Custom_</sup>                                                                                                                                                    |
| **Fonts**       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Ionicons.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Ionicons.woff2) |
| **Icons**       | [SVGs](https://github.com/iconicFonts/if/tree/main/packs/Ionicons/svgs) <sup>_1,352_</sup>                                                                                      |
| **Index**       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Ionicons.csv)                                                                                                         |
| **Codepoints**  | `U+E000..U+E546` <sup>_Custom_</sup>                                                                                                                                            |
| **Fontname**    | IoniconsIF                                                                                                                                                                      |
| **Family Name** | Ionicons IF                                                                                                                                                                     |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Ionicons_dark.png">
  <img alt="Ionicons icons preview" src="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Ionicons_light.png">
</picture>

## Installation

<details>

<summary>Linux</summary>

```sh
curl -o ~/.local/share/fonts/Ionicons.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Ionicons.ttf
```

Refresh font cache:

```sh
fc-cache -f ~/.local/share/fonts
```

</details>

<details>

<summary>macOS</summary>

```sh
curl -o ~/Library/Fonts/Ionicons.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Ionicons.ttf
```

</details>

<details>

<summary>Windows</summary>

```sh
curl -o C:\Windows\Fonts\Ionicons.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Ionicons.ttf
```

</details>

<details>

## Usage Notes

> [!NOTE]
>
> 1. The suffixes of icons were adjusted from `-outline`, `-circle`, and `sharp` to `-N`, where `N` represents a number, until a unique icon name was found.
>    2 **Ionicons** font is standalone and has its own [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Ionicons.csv), which are different from those in the [IF](https://github.com/iconicFonts/if/blob/main/indices/if.csv) font[^1].

> [!IMPORTANT]  
> The [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Ionicons.csv) for the **Ionicons** font remain unchanged and will not alter in the future, ensuring that you can use the font safely even when new versions are released.

## Support

If you've found this project helpful, a little love goes a long way. Give it a :star: or share it around.

[^1]: The first glyph for the **Ionicons** font starts from codepoint `E000`, while for the **iPack** font, it starts from `F689F`.
