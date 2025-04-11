# Atom One Light Exact

An exact recreation of the Atom One Light theme from the Atom IDE, with authentic colors and styling.

## Features

- Authentic recreation of the original Atom One Light theme
- Precisely matched color palette
- Optimized for readability
- Support for a wide range of languages

## Colors

This theme uses the exact color palette from the original Atom One Light theme:

- Background: #FAFAFA
- Foreground: #383A42
- Accent: #526FFF
- Mono-1: #383A42 (main text color)
- Mono-2: #696C77 (secondary text color)
- Mono-3: #A0A1A7 (tertiary text color)
- Cyan: #0184BC
- Blue: #4078F2
- Purple: #A626A4
- Green: #50A14F
- Red-1: #E45649
- Red-2: #CA1243
- Orange-1: #986801
- Orange-2: #C18401

## Installation

### Manual Installation

1. Download or clone this repository
2. Navigate to your VS Code extensions folder:
   - Windows: `%USERPROFILE%\.vscode\extensions`
   - macOS: `~/.vscode/extensions`
   - Linux: `~/.vscode/extensions`
3. Create a new folder named `atom-one-light-exact`
4. Copy all files from this repository into that folder
5. Restart VS Code
6. Select the theme via: `Preferences -> Color Theme -> Atom One Light Exact`

### Creating a VSIX Extension

To create a VSIX extension file that you can share or install manually:

1. Install Visual Studio Code Extension Manager (vsce):
   ```
   npm install -g vsce
   ```

2. Navigate to the extension directory and run:
   ```
   vsce package
   ```

3. Install the generated .vsix file:
   - In VS Code, open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
   - Type `Extensions: Install from VSIX...`
   - Select the .vsix file you generated

## Customization

If you want to customize any aspects of this theme, you can do so by modifying the theme file:

1. Open your VS Code settings.json
2. Add a `editor.tokenColorCustomizations` block:

```json
"editor.tokenColorCustomizations": {
  "[Atom One Light Exact]": {
    "comments": "#your-color-here",
    "strings": "#your-color-here",
    // ... and so on
  }
}
```

## License

MIT