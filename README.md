# Nocturna is a **sleek, modern, and immersive dark theme** for Visual Studio Code. Crafted for developers who prefer a minimal, focused, and visually rich coding experience — day or night.

![Nocturna Screenshot](https://raw.githubusercontent.com/shondsouza/nocturna-theme/main/assets/screenshot.png)

---

## Features

- Deep dark background with high-contrast, vibrant syntax
- Carefully tuned color palette for readability and reduced eye strain
- Focus-first design for long coding sessions
- Great for web dev, Python, JavaScript, TypeScript, and more

---

## Installation

### Option 1: From VS Code Marketplace

1. Open Extensions panel in VS Code: `Ctrl+Shift+X`
2. Search for `Nocturna Theme`
3. Click **Install** and apply the theme via `Ctrl+K Ctrl+T`

### Option 2: From VSIX File (manual)

1. Clone or download this repo
2. Run:
   ```bash
   npm install -g vsce
   vsce package
   code --install-extension nocturna-theme-*.vsix
