[preview]:              https://minidiscordthemes.github.io/Demonstration/preview/preview.png
[preview-dark]:         https://minidiscordthemes.github.io/Demonstration/preview/preview-dark.png
[preview-light]:        https://minidiscordthemes.github.io/Demonstration/preview/preview-light.png
[preview-neobrutal]:    https://minidiscordthemes.github.io/Demonstration/preview/preview-neobrutal.png
[preview-synthesis]:    https://minidiscordthemes.github.io/Demonstration/preview/preview-synthesis.png
[preview-ninex]:        https://minidiscordthemes.github.io/Demonstration/preview/preview-ninex.png
[preview-tritone]:      https://minidiscordthemes.github.io/Demonstration/preview/preview-tritone.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[css-length]:       https://developer.mozilla.org/en-US/docs/Web/CSS/length

[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/MiniDiscordThemes/Demonstration/Demonstration.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/MiniDiscordThemes/Demonstration/net.saltssaumure.Demonstration.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/Demonstration?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/MiniDiscordThemes/Demonstration
[issues]:           https://github.com/MiniDiscordThemes/Demonstration/issues
[license]:          https://github.com/MiniDiscordThemes/Demonstration/blob/main/LICENSE
[.theme.css]:       https://github.com/MiniDiscordThemes/Demonstration/blob/main/Demonstration.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.Demonstration "Replugged store page"
[release-bd-gh]:    https://github.com/MiniDiscordThemes/Demonstration/releases/latest/download/Demonstration.theme.css "Get latest release"
[release-rp-gh]:    https://github.com/MiniDiscordThemes/Demonstration/releases/latest/download/net.saltssaumure.Demonstration.asar "Get latest release"

# Demonstration Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![CSS GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Asar GitHub downloads][shield-asar-dl]][release-rp-gh]
[![Total repository size][shield-repo-size]][github]

***A Discord theme for demonstrating Discord themes.***

![Demonstration banner][preview]

| Demonstrating themes in dark mode         | Demonstrating themes in light mode         |
| ----------------------------------------- | ------------------------------------------ |
| ![Synthesis dark mode][preview-synthesis] | ![Ninex light mode][preview-ninex]         |
| ![Tritone dark mode][preview-tritone]     | ![Neobrutal light mode][preview-neobrutal] |

<!-- | ![Default dark mode][preview-dark]        | ![Default light mode][preview-light]       | -->

## Installation
Install a client mod, then follow the instructions below.

### [BetterDiscord][BetterDiscord]
<details>
    <summary>Click to expand</summary>

1. Download `Demonstration.theme.css`:
    <!-- - [BetterDiscord store][release-bd] -->
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.
</details>

### [Replugged][Replugged]
<details>
    <summary>Click to expand</summary>

#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.Demonstration.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.
</details>

### [Vencord][Vencord]
<details>
    <summary>Click to expand</summary>

#### Local
1. Download `Demonstration.theme.css`:
    <!-- - [BetterDiscord store][release-bd] -->
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://minidiscordthemes.github.io/Demonstration/Demonstration.theme.css`
</details>

## Customisation
To edit the following variables, follow the instructions for your client mod.

| Variable               | Description                          | Valid values                       | Default value |
| ---------------------- | ------------------------------------ | ---------------------------------- | ------------- |
| `--demo-font-variant`  | Font style for censored text         | `Circular` or `Rounded` or `Block` | `Circular`    |
| `--demo-font-emoji`    | Font style for emojis                | `Noto` or `none`                   | `Noto`        |
| `--demo-text`          | Toggle text censor                   | `censor` or `normal`               | `censor`      |
| `--demo-clientmod`     | Toggle client mod element visibility | `visible` or `hidden`              | `visible`     |
| `--demo-emoji-radius`  | Corner rounding for emojis           | Any [length][css-length]           | `4px`         |
| `--demo-emoji-opacity` | Opacity for emojis                   | `0` to `1`                         | `0.5`         |
| `--demo-icon-hue`      | Hue for icons, emojis, badges        | `0` to `360`                       | `240`         |
| `--demo-image-hue`     | Hue for image attachments            | `0` to `360`                       | `270`         |
| `--demo-banner-hue`    | Hue for server banners               | `0` to `360`                       | `180`         |
| `--demo-self-hue`      | Hue for your own avatar              | `0` to `360`                       | `300`         |

### BetterDiscord
<details>
    <summary>Click to expand</summary>

1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.
</details>

### Replugged
<details>
    <summary>Click to expand</summary>

1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
2. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-27 of [`Demonstration.theme.css`][.theme.css].
4. Edit the variable values and save.
</details>

### Vencord
<details>
    <summary>Click to expand</summary>

#### Local
1. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
2. Open `Demonstration.theme.css` with your favourite text editor.
3. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-27 of [`Demonstration.theme.css`][.theme.css].
3. Edit the variable values.
</details>

## License
[MIT License][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, just include the original license.

## Credits
- [Flow typeface](https://github.com/HYPD/flow-typeface) by Dan Ross - OLF-1.1 license
- [Noto Emoji](https://fonts.google.com/noto/specimen/Noto+Emoji) by Google - OLF-1.1 license

## Questions or suggestions?
- [Post an issue on GitHub.][issues]
- [Post in `#theme-support` on my support server.][discord]