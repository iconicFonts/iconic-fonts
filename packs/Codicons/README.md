# Codicons

- [**Installation**](#installation)
- [**Usage Notes**](#usage-notes)
- [**Support**](#support)

| Repo            | [microsoft/vscode-codicons](https://github.com/microsoft/vscode-codicons)                                                                                                       |
| :-------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Version**     | `v1.0.0` <sup>_Custom_</sup>                                                                                                                                                    |
| **Fonts**       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Codicons.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Codicons.woff2) |
| **Icons**       | [SVGs](https://github.com/iconicFonts/if/tree/main/packs/Codicons/svgs) <sup>_460_</sup>                                                                                        |
| **Index**       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Codicons.csv)                                                                                                         |
| **Codepoints**  | `U+E000..U+E1CA` <sup>_Custom_</sup>                                                                                                                                            |
| **Fontname**    | CodiconsIF                                                                                                                                                                      |
| **Family Name** | Codicons IF                                                                                                                                                                     |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Codicons_dark.png">
  <img alt="Codicons icons preview" src="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Codicons_light.png">
</picture>

## Installation

<details>

<summary>Linux</summary>

```sh
curl -o ~/.local/share/fonts/Codicons.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Codicons.ttf
```

Refresh font cache:

```sh
fc-cache -f ~/.local/share/fonts
```

</details>

<details>

<summary>macOS</summary>

```sh
curl -o ~/Library/Fonts/Codicons.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Codicons.ttf
```

</details>

<details>

<summary>Windows</summary>

```sh
curl -o C:\Windows\Fonts\Codicons.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Codicons.ttf
```

</details>

## Usage Notes

> [!NOTE]  
> **Codicons** font is standalone and has its own [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Codicons.csv), which are different from those in the [IF](https://github.com/iconicFonts/if/blob/main/indices/if.csv) font[^1].

> [!IMPORTANT]
> The [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Codicons.csv) for the **Codicons** font remain unchanged and will not alter in the future, ensuring that you can use the font safely even when new versions are released.

## Support

If you've found this project helpful, a little love goes a long way. Give it a :star: or share it around.

[^1]: The first glyph for the **Codicons** font starts from codepoint `E000`, while for the **iPack** font, it starts from `F04B6`.
