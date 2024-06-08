# Framework7

- [**Installation**](#installation)
- [**Usage Notes**](#usage-notes)
- [**Support**](#support)

| Repo            | [framework7io/Framework7-Icons](https://github.com/framework7io/Framework7-Icons)                                                                                                   |
| :-------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Version**     | `v1.0.0` <sup>_Custom_</sup>                                                                                                                                                        |
| **Fonts**       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Framework7.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Framework7.woff2) |
| **Icons**       | [SVGs](https://github.com/iconicFonts/if/tree/main/packs/Framework7/svgs) <sup>_1,207_</sup>                                                                                        |
| **Index**       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Framework7.csv)                                                                                                           |
| **Codepoints**  | `U+E000..U+E4B5` <sup>_Custom_</sup>                                                                                                                                                |
| **Fontname**    | Framework7IF                                                                                                                                                                        |
| **Family Name** | Framework7 IF                                                                                                                                                                       |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Framework7_dark.png">
  <img alt="Framework7 icons preview" src="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Framework7_light.png">
</picture>

## Installation

<details>

<summary>Linux</summary>

```sh
curl -o ~/.local/share/fonts/Framework7.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Framework7.ttf
```

Refresh font cache:

```sh
fc-cache -f ~/.local/share/fonts
```

</details>

<details>

<summary>macOS</summary>

```sh
curl -o ~/Library/Fonts/Framework7.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Framework7.ttf
```

</details>

<details>

<summary>Windows</summary>

```sh
curl -o C:\Windows\Fonts\Framework7.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Framework7.ttf
```

</details>

## Usage Notes

> [!NOTE]
>
> 1. The suffixes of icons were adjusted from `_square`, `_circle`, and `_fill` to `-N`, where `N` represents a number, until a unique icon name was found.
> 2. **Framework7** font is standalone and has its own [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Framework7.csv), which are different from those in the [IF](https://github.com/iconicFonts/if/blob/main/indices/if.csv) font[^1].

> [!IMPORTANT]  
> The [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Framework7.csv) for the **Framework7** font remain unchanged and will not alter in the future, ensuring that you can use the font safely even when new versions are released.

## Support

If you've found this project helpful, a little love goes a long way. Give it a :star: or share it around.

[^1]: The first glyph for the **Framework7** font starts from codepoint `E000`, while for the **iPack** font, it starts from `F0000`.
