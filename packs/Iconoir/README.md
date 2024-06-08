# Iconoir

- [**Installation**](#installation)
- [**Usage Notes**](#usage-notes)
- [**Support**](#support)

| Repo            | [iconoir-icons/iconoir](https://github.com/iconoir-icons/iconoir)                                                                                                             |
| :-------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Version**     | `v1.0.0` <sup>_Custom_</sup>                                                                                                                                                  |
| **Fonts**       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Iconoir.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Iconoir.woff2) |
| **Icons**       | [SVGs](https://github.com/iconicFonts/if/tree/main/packs/Iconoir/svgs) <sup>_1,853_</sup>                                                                                     |
| **Index**       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Iconoir.csv)                                                                                                        |
| **Codepoints**  | `U+E000..U+E62D` <sup>_Custom_</sup>                                                                                                                                          |
| **Fontname**    | IconoirIF                                                                                                                                                                     |
| **Family Name** | Iconoir IF                                                                                                                                                                    |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Iconoir_dark.png">
  <img alt="Iconoir icons preview" src="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Iconoir_light.png">
</picture>

## Installation

<details>

<summary>Linux</summary>

```sh
curl -o ~/.local/share/fonts/Iconoir.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Iconoir.ttf
```

Refresh font cache:

```sh
fc-cache -f ~/.local/share/fonts
```

</details>

<details>

<summary>macOS</summary>

```sh
curl -o ~/Library/Fonts/Iconoir.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Iconoir.ttf
```

</details>

<details>

<summary>Windows</summary>

```sh
curl -o C:\Windows\Fonts\Iconoir.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Iconoir.ttf
```

</details>

## Usage Notes

> [!NOTE]
>
> 1. The suffixes of icons were adjusted from `-square` and `-circle` to `-N`, where `N` represents a number, until a unique icon name was found.
> 2. The **Iconoir** font is standalone and has its own [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Iconoir.csv), which are different from those in the [IF](https://github.com/iconicFonts/if/blob/main/indices/if.csv) font[^1].

> [!IMPORTANT]
> The [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Iconoir.csv) for the **Iconoir** font remain unchanged and will not alter in the future, ensuring that you can use the font safely even when new versions are released.

## Support

If you've found this project helpful, a little love goes a long way. Give it a :star: or share it around.

[^1]: The first glyph for the **Iconoir** font starts from codepoint `E000`, while for the [IF](https://github.com/iconicFonts/if/blob/main/indices/if.csv) font, it starts from `F0682`.
