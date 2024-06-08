# Vaadin

- [**Installation**](#installation)
- [**Usage Notes**](#usage-notes)
- [**Support**](#support)

| Repo            | [vaadin/vaadin-icons](https://github.com/vaadin/vaadin-icons)                                                                                                               |
| :-------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Version**     | `v1.0.0` <sup>_Custom_</sup>                                                                                                                                                |
| **Fonts**       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Vaadin.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Vaadin.woff2) |
| **Icons**       | [SVGs](https://github.com/iconicFonts/if/tree/main/packs/Vaadin/svgs) <sup>_636_</sup>                                                                                      |
| **Index**       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Vaadin.csv)                                                                                                       |
| **Codepoints**  | `U+E000..U+E27A` <sup>_Custom_</sup>                                                                                                                                        |
| **Fontname**    | VaadinIF                                                                                                                                                                    |
| **Family Name** | Vaadin IF                                                                                                                                                                   |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Vaadin_dark.png">
  <img alt="Vaadin icons preview" src="https://raw.githubusercontent.com/iconicFonts/if/main/imgs/Vaadin_light.png">
</picture>

## Installation

<details>

<summary>Linux</summary>

```sh
curl -o ~/.local/share/fonts/Vaadin.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Vaadin.ttf
```

Refresh font cache:

```sh
fc-cache -f ~/.local/share/fonts
```

</details>

<details>

<summary>macOS</summary>

```sh
curl -o ~/Library/Fonts/Vaadin.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Vaadin.ttf
```

</details>

<details>

<summary>Windows</summary>

```sh
curl -o C:\Windows\Fonts\Vaadin.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Vaadin.ttf
```

</details>

## Usage Notes

> [!NOTE]
>
> 1. The suffixes of icons were adjusted from `-square` and `-circle` to `-N`, where `N` represents a number, until a unique icon name was found.
> 2. \*Vaadin** font is standalone and has its own [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Vaadin.csv), which are different from those in the **iPack\*\* fonts[^1].

> [!IMPORTANT]
> The [codepoints](https://github.com/iconicFonts/if/blob/main/indices/Vaadin.csv) for the **Vaadin** font remain unchanged and will not alter in the future, ensuring that you can use the font safely even when new versions are released.

## Support

If you've found this project helpful, a little love goes a long way. Give it a :star: or share it around.

[^1]: The first glyph for the **Vaadin** font starts from codepoint `E000`, while for the **iPack** font, it starts from `F4B83`.
