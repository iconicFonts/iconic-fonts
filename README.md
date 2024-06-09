[![Ceasefire Now](https://badge.techforpalestine.org/default)](https://techforpalestine.org/learn-more)

# Iconic Fonts

**Iconic Fonts (IF)** offers over **55,000** icons collected from **43** different icon sets. These icons are available either as a single iconic font or as separate fonts based on the icon set.

> [!NOTE]
> This project is still under development.

## Table of Contents

- [Installation](#installation)
- [Supported Packs](#supported-packs)
- [Searching Glyphs](#searching-glyphs)
- [Tools Used in this Project](#tools-used-in-this-project)
- [Licensing](#licensing)

## Installation

### Manual Installation

To manually install a pack, download its font individually from the supported packs, or download the [IF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/if.ttf) font that includes all icon packs. After downloading the font(s), copy them to:

- **Linux:** `~/.local/share/fonts`
- **macOS:** `~/Library/Fonts/`
- **Windows:** `C:\Windows\Fonts\`

### Using curl

<details>

<summary>Linux</summary>

```sh
curl -o ~/.local/share/fonts/packName.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/packName.ttf
```

Refresh font cache:

```sh
fc-cache -f ~/.local/share/fonts
```

</details>

<details>

<summary>macOS</summary>

```sh
curl -o ~/Library/Fonts/packName.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/packName.ttf
```

</details>

<details>

<summary>Windows</summary>

```sh
curl -o C:\Windows\Fonts\packName.ttf https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/packName.ttf
```

</details>

> [!NOTE]
> Ensure that you replace `packNames` with the desired [pack name](https://github.com/iconicFonts/if/tree/main/packs).

## Supported Packs


| Pack                                                                                 | Fonts                                                                                                                                                                                         | Index                                                                          |
| ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| [Academia](https://github.com/iconicFonts/if/tree/main/packs/Academia)               | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Academia.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Academia.woff2)               | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Academia.csv)        |
| [AntDesign](https://github.com/iconicFonts/if/tree/main/packs/AntDesign)             | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/AntDesign.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/AntDesign.woff2)             | [CSV](https://github.com/iconicFonts/if/blob/main/indices/AntDesign.csv)       |
| [Box](https://github.com/iconicFonts/if/tree/main/packs/Box)                         | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Box.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Box.woff2)                         | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Box.csv)             |
| [Chess](https://github.com/iconicFonts/if/tree/main/packs/Chess)                     | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Chess.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Chess.woff2)                     | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Chess.csv)           |
| [Circum](https://github.com/iconicFonts/if/tree/main/packs/Circum)                   | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Circum.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Circum.woff2)                   | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Circum.csv)          |
| [Codicons](https://github.com/iconicFonts/if/tree/main/packs/Codicons)               | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Codicons.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Codicons.woff2)               | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Codicons.csv)        |
| [CoreUi](https://github.com/iconicFonts/if/tree/main/packs/CoreUi)                   | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/CoreUi.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/CoreUi.woff2)                   | [CSV](https://github.com/iconicFonts/if/blob/main/indices/CoreUi.csv)          |
| [Crypto](https://github.com/iconicFonts/if/tree/main/packs/Crypto)                   | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Crypto.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Crypto.woff2)                   | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Crypto.csv)          |
| [CSS](https://github.com/iconicFonts/if/tree/main/packs/CSS)                         | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/CSS.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/CSS.woff2)                         | [CSV](https://github.com/iconicFonts/if/blob/main/indices/CSS.csv)             |
| [Devicon](https://github.com/iconicFonts/if/tree/main/packs/Devicon)                 | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Devicon.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Devicon.woff2)                 | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Devicon.csv)         |
| [Eva](https://github.com/iconicFonts/if/tree/main/packs/Eva)                         | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Eva.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Eva.woff2)                         | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Eva.csv)             |
| [Feather](https://github.com/iconicFonts/if/tree/main/packs/Feather)                 | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Feather.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Feather.woff2)                 | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Feather.csv)         |
| [File](https://github.com/iconicFonts/if/tree/main/packs/File)                       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/File.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/File.woff2)                       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/File.csv)            |
| [FontAwesome](https://github.com/iconicFonts/if/tree/main/packs/FontAwesome)         | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/FontAwesome.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/FontAwesome.woff2)         | [CSV](https://github.com/iconicFonts/if/blob/main/indices/FontAwesome.csv)     |
| [Framework7](https://github.com/iconicFonts/if/tree/main/packs/Framework7)           | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Framework7.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Framework7.woff2)           | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Framework7.csv)      |
| [Game](https://github.com/iconicFonts/if/tree/main/packs/Game)                       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Game.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Game.woff2)                       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Game.csv)            |
| [Grommet](https://github.com/iconicFonts/if/tree/main/packs/Grommet)                 | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Grommet.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Grommet.woff2)                 | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Grommet.csv)         |
| [Hero](https://github.com/iconicFonts/if/tree/main/packs/Hero)                       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Hero.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Hero.woff2)                       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Hero.csv)            |
| [IcoMoon](https://github.com/iconicFonts/if/tree/main/packs/IcoMoon)                 | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/IcoMoon.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/IcoMoon.woff2)                 | [CSV](https://github.com/iconicFonts/if/blob/main/indices/IcoMoon.csv)         |
| [Iconoir](https://github.com/iconicFonts/if/tree/main/packs/Iconoir)                 | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Iconoir.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Iconoir.woff2)                 | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Iconoir.csv)         |
| [IconPark](https://github.com/iconicFonts/if/tree/main/packs/IconPark)               | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/IconPark.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/IconPark.woff2)               | [CSV](https://github.com/iconicFonts/if/blob/main/indices/IconPark.csv)        |
| [Ionicons](https://github.com/iconicFonts/if/tree/main/packs/Ionicons)               | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Ionicons.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Ionicons.woff2)               | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Ionicons.csv)        |
| [LegacyComputing](https://github.com/iconicFonts/if/tree/main/packs/LegacyComputing) | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/LegacyComputing.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/LegacyComputing.woff2) | [CSV](https://github.com/iconicFonts/if/blob/main/indices/LegacyComputing.csv) |
| [Linea](https://github.com/iconicFonts/if/tree/main/packs/Linea)                     | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Linea.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Linea.woff2)                     | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Linea.csv)           |
| [LineAwesome](https://github.com/iconicFonts/if/tree/main/packs/LineAwesome)         | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/LineAwesome.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/LineAwesome.woff2)         | [CSV](https://github.com/iconicFonts/if/blob/main/indices/LineAwesome.csv)     |
| [Logos](https://github.com/iconicFonts/if/tree/main/packs/Logos)                     | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Logos.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Logos.woff2)                     | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Logos.csv)           |
| [Lucide](https://github.com/iconicFonts/if/tree/main/packs/Lucide)                   | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Lucide.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Lucide.woff2)                   | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Lucide.csv)          |
| [MaterialDesign](https://github.com/iconicFonts/if/tree/main/packs/MaterialDesign)   | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/MaterialDesign.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/MaterialDesign.woff2)   | [CSV](https://github.com/iconicFonts/if/blob/main/indices/MaterialDesign.csv)  |
| [Mfizz](https://github.com/iconicFonts/if/tree/main/packs/Mfizz)                     | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Mfizz.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Mfizz.woff2)                     | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Mfizz.csv)           |
| [Octicons](https://github.com/iconicFonts/if/tree/main/packs/Octicons)               | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Octicons.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Octicons.woff2)               | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Octicons.csv)        |
| [Open](https://github.com/iconicFonts/if/tree/main/packs/Open)                       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Open.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Open.woff2)                       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Open.csv)            |
| [Payment](https://github.com/iconicFonts/if/tree/main/packs/Payment)                 | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Payment.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Payment.woff2)                 | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Payment.csv)         |
| [Phosphor](https://github.com/iconicFonts/if/tree/main/packs/Phosphor)               | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Phosphor.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Phosphor.woff2)               | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Phosphor.csv)        |
| [Remix](https://github.com/iconicFonts/if/tree/main/packs/Remix)                     | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Remix.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Remix.woff2)                     | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Remix.csv)           |
| [Siji](https://github.com/iconicFonts/if/tree/main/packs/Siji)                       | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Siji.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Siji.woff2)                       | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Siji.csv)            |
| [Simple](https://github.com/iconicFonts/if/tree/main/packs/Simple)                   | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Simple.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Simple.woff2)                   | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Simple.csv)          |
| [SimpleLine](https://github.com/iconicFonts/if/tree/main/packs/SimpleLine)           | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/SimpleLine.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/SimpleLine.woff2)           | [CSV](https://github.com/iconicFonts/if/blob/main/indices/SimpleLine.csv)      |
| [Social](https://github.com/iconicFonts/if/tree/main/packs/Social)                   | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Social.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Social.woff2)                   | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Social.csv)          |
| [Tabler](https://github.com/iconicFonts/if/tree/main/packs/Tabler)                   | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Tabler.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Tabler.woff2)                   | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Tabler.csv)          |
| [Themify](https://github.com/iconicFonts/if/tree/main/packs/Themify)                 | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Themify.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Themify.woff2)                 | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Themify.csv)         |
| [Typicons](https://github.com/iconicFonts/if/tree/main/packs/Typicons)               | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Typicons.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Typicons.woff2)               | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Typicons.csv)        |
| [Vaadin](https://github.com/iconicFonts/if/tree/main/packs/Vaadin)                   | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Vaadin.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Vaadin.woff2)                   | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Vaadin.csv)          |
| [Weather](https://github.com/iconicFonts/if/tree/main/packs/Weather)                 | [TTF](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/TTF/Weather.ttf) - [WOFF2](https://raw.githubusercontent.com/iconicFonts/if/main/fonts/WOFF2/Weather.woff2)                 | [CSV](https://github.com/iconicFonts/if/blob/main/indices/Weather.csv)         |

## Searching Glyphs

Searching for glyphs using [FZF](https://junegunn.github.io/fzf/) is a breeze. Just download the desired [pack index](https://github.com/iconicFonts/if/tree/main/indices) and replace `packName.csv` with its path.

```sh
column -t -s ',' -o $'\t' packName.csv |
fzf -d '\t' --with-nth=1,2 --header-lines=1 \
--bind 'enter:close+execute(echo {1})'
```

## Tools Used in this Project

- [Inkscape](https://inkscape.org): Converts strokes to fills and creates PNG icon previews.
- [SVGO](https://svgo.dev): Decreases icon sizes and optimizes them.
- [FontForge](https://fontforge.org/): Generates the fonts.
- [ImageMagick](https://www.imagemagick.org/script/magick.php): Compresses PNG files.
- [jq](https://jqlang.github.io/jq/): A command-line JSON processor to handle pack configurations.
- [FZF](https://junegunn.github.io/fzf/installation/): Searching glyphs.

## Licensing

- **Fonts**: All Fonts in this project are licensed under a [OFL 1.1 ](https://openfontlicense.org/documents/OFL.txt) and applies to all TTF and WOFF2 file types.
- **Icons**: The license for each SVGs folder applies to all SVG files within, reflecting the individual terms of their respective sources.
- **Files**: All non-font and non-icon files in this project are licensed under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) License.

Please refer to the [LICENSE](https://github.com/iconicFonts/if/blob/main/LICENSE) file for more details.
