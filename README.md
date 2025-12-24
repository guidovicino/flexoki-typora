# Flexoki Light Theme for Typora

An inky, warm color theme for Typora based on the [Flexoki](https://stephango.com/flexoki) color palette by [Steph Ango](https://stephango.com/).

Flexoki is inspired by analog inks and warm shades of paper, designed for reading and writing on digital screens. This theme brings that same warmth and readability to your Markdown editing experience in Typora.

## Features

- **Warm, paper-like aesthetics** - Inspired by analog ink on paper
- **High contrast** - Optimized for legibility across devices
- **Minimalist design** - Clean and distraction-free writing environment
- **Complete syntax highlighting** - Thoughtful color mapping for code blocks
- **Modern typography** - Uses Inter font for excellent readability
- **Monospace code** - JetBrainsMono Nerd Font for code blocks
- **Focus mode support** - Elegant fade effect for non-focused content
- **Print optimized** - Clean export to PDF

## Color Palette

The theme uses the Flexoki Light palette with the following mappings:

- **Background**: `#FFFCF0` (paper) - A warm, off-white background
- **Text**: `#100F0F` (black) - Deep, rich black for optimal readability
- **Headings**: `#100F0F` (black) - Strong, clear hierarchy
- **Links**: `#24837B` (cyan-600) - Warm, accessible accent color (underlined)
- **Blockquote border**: `#24837B` (cyan-600) - 2px left border, no background
- **List markers**: `#B7B5AC` (base-300) - Light gray for bullets and numbers
- **Code background**: `#F2F0E5` (base-50) - Subtle contrast
- **Accents**: Full Flexoki palette for syntax highlighting

### Syntax Highlighting

- **Keywords**: Green (`#66800B`)
- **Strings**: Cyan (`#24837B`)
- **Functions**: Orange (`#BC5215`)
- **Numbers**: Purple (`#5E409D`)
- **Comments**: Gray (`#B7B5AC`, italic)
- **Constants**: Yellow (`#AD8301`)
- **Variables**: Blue (`#205EA6`)
- **Links & UI Accents**: Cyan (`#24837B`)

## Installation

### 1. Install the Theme

1. Download `flexoki-light.css` from this repository
2. Open Typora and go to **Preferences** → **Appearance** → **Open Theme Folder**
3. Copy `flexoki-light.css` to the themes folder
4. Restart Typora
5. Go to **Themes** menu and select **Flexoki Light**

### 2. Install Fonts (Recommended)

For the best experience, install the recommended fonts:

#### Inter (Body Font)

**Option 1 - Google Fonts (Easy)**
- Visit [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- Click "Download family" and install the fonts on your system

**Option 2 - Official Site**
- Visit [rsms.me/inter](https://rsms.me/inter/)
- Download and install the variable font

**Linux Installation:**
```bash
# Download Inter
wget https://github.com/rsms/inter/releases/download/v4.0/Inter-4.0.zip
unzip Inter-4.0.zip -d Inter
# Install
mkdir -p ~/.local/share/fonts
cp Inter/Inter\ Desktop/*.otf ~/.local/share/fonts/
fc-cache -f -v
```

#### JetBrainsMono Nerd Font (Code Font)

**Option 1 - Nerd Fonts (Recommended)**
- Visit [Nerd Fonts](https://www.nerdfonts.com/)
- Download [JetBrainsMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/latest)
- Install the fonts on your system

**Option 2 - Official JetBrains Mono**
- Visit [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
- Download and install the fonts

**Linux Installation:**
```bash
# Download JetBrainsMono Nerd Font
wget https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip
unzip JetBrainsMono.zip -d JetBrainsMono
# Install
mkdir -p ~/.local/share/fonts
cp JetBrainsMono/*.ttf ~/.local/share/fonts/
fc-cache -f -v
```

**Note:** The theme will work without these fonts, falling back to system defaults:
- Body text: system-ui or similar sans-serif fonts
- Code: Fira Code, Consolas, or system monospace fonts

### 3. Verify Installation

1. Restart Typora
2. Go to **Themes** menu
3. Select **Flexoki Light**
4. The theme should be active with warm, paper-like colors

## Screenshots

<!-- Add screenshots here when available -->
*Screenshots coming soon*

## Customization

You can customize the theme by editing `flexoki-light.css`. All colors are defined as CSS variables in the `:root` section at the top of the file.

### Common Customizations

**Change writing area width:**
```css
#write {
  max-width: 860px; /* Change this value */
}
```

**Change base font size:**
```css
html {
  font-size: 16px; /* Change this value */
}
```

**Use different fonts:**
```css
:root {
  --sans-serif: "Your Font", sans-serif;
  --monospace: "Your Mono Font", monospace;
}
```

## Compatibility

- **Tested on**: Linux (should work on macOS and Windows)
- **Typora Version**: 1.0+
- **Supports**: All Markdown features including tables, code blocks, math, diagrams

## What's Included

This theme provides complete styling for:

- ✅ All Markdown elements (headings, lists, quotes, etc.)
- ✅ Code blocks with syntax highlighting
- ✅ Tables with alternating rows
- ✅ Images with subtle shadows
- ✅ Links and emphasis
- ✅ Sidebar and file browser
- ✅ Search panel
- ✅ Footer and status bar
- ✅ Context menus and dialogs
- ✅ Focus mode
- ✅ Source code mode
- ✅ Print/PDF export styles
- ✅ Mermaid diagrams
- ✅ Math equations (MathJax)

## Credits

- **Flexoki Color Palette**: Created by [Steph Ango](https://stephango.com/flexoki)
- **Typora Theme**: Created by [Your Name]
- **Inter Font**: Created by [Rasmus Andersson](https://rsms.me/inter/)
- **JetBrainsMono**: Created by [JetBrains](https://www.jetbrains.com/lp/mono/)

## License

This theme is released under the MIT License, matching the Flexoki color palette license.

```
MIT License

Copyright (c) 2024 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Contributing

Issues and pull requests are welcome! If you find a bug or have a suggestion:

1. Check if an issue already exists
2. If not, create a new issue with a clear description
3. For pull requests, please maintain the existing code style

## Future Plans

- [ ] Dark mode variant (`flexoki-dark.css`)
- [ ] Additional color accent options
- [ ] More diagram styling (sequence, gantt, etc.)
- [ ] Custom export templates

## Support

If you enjoy this theme, consider:
- ⭐ Starring this repository
- 🔗 Sharing it with other Typora users
- 📝 Writing about it or creating tutorials
- ☕ Supporting the original [Flexoki project](https://github.com/kepano/flexoki)

## Links

- [Flexoki Official Site](https://stephango.com/flexoki)
- [Flexoki GitHub Repository](https://github.com/kepano/flexoki)
- [Typora Official Site](https://typora.io/)
- [Typora Theme Documentation](https://theme.typora.io/)

---

**Enjoy writing with Flexoki! 📝✨**
