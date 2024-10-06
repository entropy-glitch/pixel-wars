# Pixel Wars ✨

A VSCode theme extension that brings iconic, pixel-inspired galactic themes to your coding environment with Pixel Wars. Experience the shades of Darth Invader, Luke Skywriter and Storm Tracker as you code.

Pixel Wars offers a cohesive and immersive coding experience by harmonizing every element—from the sidebar to the integrated terminal—with your selected theme.

![GitHub issues](https://img.shields.io/github/issues/entropy-glitch/pixel-wars)
![GitHub pull requests](https://img.shields.io/github/issues-pr/entropy-glitch/pixel-wars)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![GitHub stars](https://img.shields.io/github/stars/entropy-glitch/pixel-wars?style=social)

![Header Image](./artworks/header.png)

## Usage 🚀

Switch between different themes to experience the unique ambiance each one brings to your coding environment. Preview the themes below to find your favorite!

![Darth Invader Theme](./artworks/darthInvader.png)

<br></br>

![Luke Skywalker Theme](./artworks/lukeSkywriter.png)

<br></br>

![Storm Tracker Theme](./artworks/stormTracker.png)

<br></br>

## Table of Contents

- [Installation](#installation)
- [Recommended Font: JetBrains Mono](#recommended-font-jetbrains-mono)
  - [How to Install JetBrains Mono](#how-to-install-jetbrains-mono)
  - [Setting JetBrains Mono in VSCode](#setting-jetbrains-mono-in-vscode)
- [Special Instructions for Linux Users](#special-instructions-for-linux-users)
  - [Enabling Custom Components](#enabling-custom-components)
- [Features](#features)
- [Support](#support)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Changelog](#changelog)
- [FAQs](#faqs)
- [Contact](#contact)

## Installation 💾

1. Open the Extensions sidebar in VSCode. `View → Extensions`.
2. Search for `Pixel Wars`, and install it.
3. After installation, select the theme by navigating to `File → Preferences → Color Theme → Pixel Wars`.

### 🌌 Quick Theme Change in VSCode 🎹

To enhance your coding experience with Pixel Wars, follow these easy steps:

1. **Open Command Palette**: Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS) to bring up the Command Palette.

2. **Choose Theme**: Type `Preferences: Color Theme` and hit `Enter`. This action will take you directly to the theme selection menu.

3. **Select Pixel Wars**: Scroll through the list or type the name of your desired Pixel Wars theme (like Darth Invader or Luke Skywriter) and press `Enter` to apply it.

### 🕹️ Quick Shortcut

For an even quicker theme change:

- Press `Ctrl + K`, then `Ctrl + T`.
- This key combination instantly opens the theme selection menu. Choose your desired Pixel Wars theme from the dropdown.

## Recommended Font: JetBrains Mono ✍️

To elevate your coding experience with Pixel Wars, we recommend using the JetBrains Mono font. This font is designed specifically for developers, offering improved readability and a modern, clean aesthetic that complements the theme's styles.

### How to Install JetBrains Mono

1. Download the latest version of JetBrains Mono from the [official website](https://www.jetbrains.com/lp/mono/).
2. Unzip the downloaded archive.
3. Install the font on your system:
   - **Windows**: Right-click on the `.ttf` files and select "Install".
   - **macOS**: Double-click on the `.ttf` files and press "Install Font".
   - **Linux**: Place the `.ttf` files into `~/.local/share/fonts` (or `/usr/share/fonts` to install fonts system-wide) and run `fc-cache -f -v`.

### Setting JetBrains Mono in VSCode

After installing the font, set it as your editor's font in VSCode:

1. Open VSCode settings (`Ctrl + ,` or `Cmd + ,` on macOS).
2. Search for `Font Family`.
3. Enter `JetBrains Mono` as the first choice in the font list.
4. Ensure `Editor: Font Ligatures` is enabled to enjoy the full visual experience.

Below are some recommended settings:

```json
 "editor.fontSize": 16,
 "editor.fontFamily": "'JetBrains Mono', 'Courier New', monospace",
 "editor.fontLigatures": true,
 "terminal.integrated.fontSize": 16,
```

## Special Instructions for Linux Users 🐧

For Linux users, to fully experience the Pixel Wars theme as intended, you may need to enable certain features manually due to differences in how themes interact with the VSCode UI on Linux.

### Enabling Custom Components

1. Open the Command Palette with `Ctrl+Shift+P`.
2. Type `Preferences: Open Settings (JSON)` and press `Enter`.
3. Add or modify the following setting:

   ```json
   "window.titleBarStyle": "custom"
   ```

4. Save the settings and restart VSCode.

## Features 🌟

Pixel Wars is a collection of themes inspired by iconic galactic characters. Each theme offers a unique coding ambiance to enhance your VSCode experience.

## Support 🚑

Encountered a bug or have a suggestion? Open an issue [here](https://github.com/entropy-glitch/pixel-wars/issues) and we'll look into it.

## Contributing 🤝

We welcome contributions from the community! If you'd like to contribute, feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License ⚖️

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE) file for details.

## Acknowledgments 👏

Special thanks to the galactic pixel themes that influenced the color palettes of Pixel Wars.

## Changelog 📅

- 0.0.1 (2024-10-01): Initial release of Pixel Wars.

## FAQs ❓

- **How do I switch between different themes?**
  - Navigate to `File → Preferences → Color Theme` and select your desired theme from Pixel Wars.

## Contact

Feel free to reach out on [GitHub](https://github.com/entropy-glitch).
