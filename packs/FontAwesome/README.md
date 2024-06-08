# FontAwesome

- [**Installation**](#installation)
- [**Usage Notes**](#usage-notes)
- [**Support**](#support)

| Repo            | [FortAwesome/Font-Awesome](https://github.com/FortAwesome/Font-Awesome)                                                                                                               |
| :-------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Version**     | `v1.0.0` <sup>_Custom_</sup>                                                                                                                                                          |
| **Fonts**       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/FontAwesome.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/FontAwesome.woff2) |
| **Icons**       | [SVGs](https://github.com/iconicFonts/if/tree/main/packs/FontAwesome/svgs) <sup>_1,612_</sup>                                                                                         |
| **Index**       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/FontAwesome.csv)                                                                                                            |
| **Codepoints**  | `U+E000..U+E64A` <sup>_Custom_</sup>                                                                                                                                                  |
| **Fontname**    | FontAwesomeIF                                                                                                                                                                         |
| **Family Name** | FontAwesome IF                                                                                                                                                                        |
|                 |                                                                                                                                                                                       |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/FontAwesome_dark.png">
  <img alt="FontAwesome icons preview" src="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/FontAwesome_light.png">
</picture>

## Installation

<details>

<summary>Linux</summary>

```sh
curl -o ~/.local/share/fonts/FontAwesome.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/FontAwesome.ttf
```

Refresh font cache:

```sh
fc-cache -f ~/.local/share/fonts
```

</details>

<details>

<summary>macOS</summary>

```sh
curl -o ~/Library/Fonts/FontAwesome.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/FontAwesome.ttf
```

</details>

<details>

<summary>Windows</summary>

```sh
curl -o C:\Windows\Fonts\FontAwesome.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/FontAwesome.ttf
```

</details>

## Usage Notes

> [!NOTE]  
> **FontAwesome** font is standalone and has its own [codepoints](https://github.com/iconicFonts/if/blob/main/indices/FontAwesome.csv), which are different from those in the **iPack**[^1].

> [!IMPORTANT]
> The [codepoints](https://github.com/iconicFonts/if/blob/main/indices/FontAwesome.csv) for the **FontAwesome** font remain unchanged and will not alter in the future, ensuring that you can use the font safely even when new versions are released.

## Support

If you've found this project helpful, a little love goes a long way. Give it a :star: or share it around.

[^1]: The first glyph for the **FontAwesome** font starts from codepoint `E000`, while for the **iPack** font, it starts from `F434E`.
