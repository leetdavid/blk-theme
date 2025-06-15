# BLK Theme

<p align="center">
  <img src="https://raw.githubusercontent.com/leetdavid/blk-theme/tree/main/assets/8x/blk.png" alt="BLK Theme Logo" width="150">
</p>

<p align="center">
  A sleek, minimalist dark theme for Visual Studio Code with a true black background.
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=leetdavid.blk-theme">
    <img src="https://img.shields.io/visual-studio-marketplace/v/leetdavid.blk-theme.svg?style=flat-square&label=VS%20Marketplace&logo=visual-studio-code" alt="Visual Studio Marketplace Version">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=leetdavid.blk-theme">
    <img src="https://img.shields.io/visual-studio-marketplace/d/leetdavid.blk-theme.svg?style=flat-square&label=Downloads&logo=visual-studio-code" alt="Visual Studio Marketplace Downloads">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=leetdavid.blk-theme">
    <img src="https://img.shields.io/visual-studio-marketplace/r/leetdavid.blk-theme.svg?style=flat-square&label=Rating&logo=visual-studio-code" alt="Visual Studio Marketplace Rating">
  </a>
</p>

## Features

- **True Black Background**: Perfect for OLED displays and dark environment coding
- **High Contrast Syntax Highlighting**: Carefully selected colors for optimal readability
- **Semantic Highlighting**: Enhanced code understanding with semantic token coloring
- **Two Variants**: Standard and Borderless options to suit your preference
- **Optimized for Long Sessions**: Reduced eye strain during extended coding sessions
- **Language Support**: Extensive language-specific syntax highlighting

## Installation

1. Open **Extensions** sidebar in VS Code (`Ctrl+Shift+X` / `⌘+Shift+X`)
2. Search for `BLK Theme`
3. Click **Install**
4. Click **Reload** to activate
5. Open the **Command Palette** (`Ctrl+Shift+P` / `⌘+Shift+P`) and select **Preferences: Color Theme**
6. Select either **BLK** or **BLK Borderless**

## Screenshots

### Python

![Python Example](https://raw.githubusercontent.com/leetdavid/blk-theme/main/screenshots/python.png)

### Next.js/TSX/Typescript/Javascript

![HTML/CSS Example](https://raw.githubusercontent.com/leetdavid/blk-theme/main/screenshots/nextjs.png)

## Theme Variants

### BLK (Standard)

The standard variant includes subtle borders between UI elements for clear visual separation.

### BLK Borderless (Work in Progress)

The borderless variant minimizes borders for a more seamless, distraction-free coding experience.

## Color Palette

The BLK theme uses a carefully selected color palette:

| Scope         | Color  | Hex       |
| ------------- | ------ | --------- |
| Background    | Black  | `#000000` |
| Foreground    | White  | `#FFFFFF` |
| Strings       | Green  | `#98c379` |
| Keywords      | Purple | `#c678dd` |
| Functions     | Blue   | `#61afef` |
| Variables     | Red    | `#e06c75` |
| Types/Classes | Yellow | `#e5c07b` |
| Constants     | Orange | `#d19a66` |
| Comments      | Gray   | `#7f848e` |
| Operators     | Cyan   | `#56b6c2` |

## Recommended Settings

For the best experience with BLK Theme, consider these settings:

```json
{
  "editor.fontFamily": "'Comic Code Ligatures', 'JetBrains Mono', Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.5,
  "editor.cursorBlinking": "phase",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.renderLineHighlight": "all",
  "workbench.colorCustomizations": {
    "[BLK]": {
      // Add your custom overrides here
    }
  }
}
```

> **Font Recommendation**: [Comic Code Ligatures](https://fonts.ilovetypography.com/fonts/tabular-type-foundry/comic-code) is a fantastic coding font that combines readability with personality.

## Customization

You can customize the BLK theme by adding overrides in your `settings.json`:

```json
"workbench.colorCustomizations": {
  "[BLK]": {
    "editor.background": "#000000",
    "editor.foreground": "#ffffff",
    // Add more customizations as needed
  }
}
```

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests on the [GitHub repository](https://github.com/leetdavid/blk-theme).

## License

This theme is released under the [MIT License](LICENSE).

## Acknowledgements

BLK Theme was inspired by various dark themes in the VS Code ecosystem, with a focus on creating a true black background experience optimized for OLED displays and night-time coding with a rainbow effect (I like rainbows).

**Enjoy coding in the dark!**
