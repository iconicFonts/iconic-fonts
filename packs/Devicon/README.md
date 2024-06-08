# Devicon

- [**Installation**](#installation)
- [**Usage Notes**](#usage-notes)
- [**Support**](#support)

| Repo            | [devicons/devicon](https://github.com/devicons/devicon)                                                                                                                       |
| :-------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Version**     | `v1.0.0` <sup>_Custom_</sup>                                                                                                                                                  |
| **Fonts**       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Devicon.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Devicon.woff2) |
| **Icons**       | [SVGs](https://github.com/iconicFonts/if/tree/main/packs/Devicon/svgs) <sup>_819_</sup>                                                                                       |
| **Index**       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Devicon.csv)                                                                                                        |
| **Codepoints**  | `U+E000..U+E331` <sup>_Custom_</sup>                                                                                                                                          |
| **Fontname**    | DeviconIF                                                                                                                                                                     |
| **Family Name** | Devicon IF                                                                                                                                                                    |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Devicon_dark.png">
  <img alt="Devicon icons preview" src="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Devicon_light.png">
</picture>

## Installation

<details>

<summary>Linux</summary>

```sh
curl -o ~/.local/share/fonts/Devicon.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Devicon.ttf

# Refresh the font cache:
fc-cache -f ~/.local/share/fonts
```

</details>

<details>

<summary>macOS</summary>

```sh
curl -o ~/Library/Fonts/Devicon.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Devicon.ttf
```

</details>

<details>

<summary>Windows</summary>

```sh
curl -o C:\Windows\Fonts\Devicon.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Devicon.ttf
```

</details>

## Usage Notes

> [!NOTE]
> The **Devicon** font is standalone and has its own [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Devicon.csv), which are different from those in the [IF](https://github.com/iconicFonts/if/blob/main/indices/if.csv) font[^1].

> [!IMPORTANT]
> The [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Devicon.csv) for the **Devicon** font remain unchanged and will not alter in the future, ensuring that you can use the font safely even when new versions are released.

## Support

If you've found this project helpful, a little love goes a long way. Give it a :star: or share it around.

[^1]: The first glyph for the **Devicon** font starts from codepoint `E000`, while for the [IF](https://github.com/iconicFonts/if/blob/main/indices/if.csv) font, it starts from `F3A69`.
