# Quick Installation Guide

## For Linux Users

### 1. Install the Theme

```bash
# Navigate to Typora themes folder
cd ~/.config/Typora/themes/

# Download the theme (if you have the file locally)
cp /path/to/flexoki-light.css .

# Or download directly from repository
# wget https://raw.githubusercontent.com/yourusername/flexoki-typora/main/flexoki-light.css
```

### 2. Install Fonts (Optional but Recommended)

#### Install Inter Font

```bash
# Download Inter
cd /tmp
wget https://github.com/rsms/inter/releases/download/v4.0/Inter-4.0.zip
unzip Inter-4.0.zip -d Inter

# Install fonts
mkdir -p ~/.local/share/fonts/inter
cp Inter/Inter\ Desktop/*.otf ~/.local/share/fonts/inter/

# Update font cache
fc-cache -f -v
```

#### Install JetBrainsMono Nerd Font

```bash
# Download JetBrainsMono Nerd Font
cd /tmp
wget https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip
unzip JetBrainsMono.zip -d JetBrainsMono

# Install fonts
mkdir -p ~/.local/share/fonts/jetbrains-mono
cp JetBrainsMono/*.ttf ~/.local/share/fonts/jetbrains-mono/

# Update font cache
fc-cache -f -v
```

### 3. Apply the Theme

1. Restart Typora
2. Go to **File** → **Preferences** → **Appearance**
3. Select **Flexoki Light** from the themes dropdown
4. Enjoy your new warm, paper-like writing environment!

## For macOS Users

### 1. Install the Theme

```bash
# Navigate to Typora themes folder
cd ~/Library/Application\ Support/abnerworks.Typora/themes/

# Copy the theme file
cp /path/to/flexoki-light.css .
```

### 2. Install Fonts

#### Using Homebrew (recommended)

```bash
# Install fonts with Homebrew
brew tap homebrew/cask-fonts
brew install --cask font-inter
brew install --cask font-jetbrains-mono-nerd-font
```

#### Manual Installation

1. Download fonts as described in the main README
2. Open Font Book
3. Drag and drop the font files
4. Click "Install Font"

### 3. Apply the Theme

1. Restart Typora
2. Go to **Typora** → **Preferences** → **Appearance**
3. Select **Flexoki Light** from the themes dropdown

## For Windows Users

### 1. Install the Theme

1. Open Typora
2. Go to **File** → **Preferences** → **Appearance** → **Open Theme Folder**
3. Copy `flexoki-light.css` to this folder
4. Restart Typora

### 2. Install Fonts

#### Inter Font

1. Download Inter from [Google Fonts](https://fonts.google.com/specimen/Inter) or [official site](https://rsms.me/inter/)
2. Extract the ZIP file
3. Open the folder containing the font files
4. Select all `.ttf` or `.otf` files
5. Right-click and select "Install" or "Install for all users"

#### JetBrainsMono Nerd Font

1. Download from [Nerd Fonts releases](https://github.com/ryanoasis/nerd-fonts/releases/latest)
2. Look for `JetBrainsMono.zip`
3. Extract the ZIP file
4. Select all `.ttf` files
5. Right-click and select "Install" or "Install for all users"

### 3. Apply the Theme

1. Restart Typora
2. Go to **File** → **Preferences** → **Appearance**
3. Select **Flexoki Light** from the themes dropdown

## Verification

To verify the theme is working correctly:

1. Open the included `EXAMPLE.md` file in Typora
2. Check that:
   - Background is warm off-white (`#FFFCF0`)
   - Headings are blue
   - Code blocks have syntax highlighting
   - Tables have alternating row colors
   - Links are blue and underline on hover

## Troubleshooting

### Theme doesn't appear in menu

- Make sure the file is named exactly `flexoki-light.css` (all lowercase, no spaces)
- Verify the file is in the correct themes folder
- Restart Typora completely (quit and reopen)

### Fonts not working

- Verify fonts are installed: Open a font viewer and search for "Inter" and "JetBrainsMono"
- After installing fonts, restart Typora
- If fonts still don't work, the theme will fall back to system fonts (still looks good!)

### Colors look different

- Make sure you selected "Flexoki Light" not another theme
- Check your OS display settings (night mode, color calibration)
- Some monitors may display colors slightly differently

## Getting Help

If you encounter issues:

1. Check the main [README.md](README.md) for detailed information
2. Open an issue on GitHub with:
   - Your operating system and version
   - Typora version
   - Description of the problem
   - Screenshots if applicable

## Uninstallation

To remove the theme:

1. Go to Typora themes folder (see installation instructions above)
2. Delete `flexoki-light.css`
3. Restart Typora

The fonts will remain installed for use with other applications.
