# Changelog

All notable changes to the Flexoki Light theme for Typora will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2024-12-24

### Added - Initial Release

**Complete Flexoki Light Theme Implementation**
- Full Flexoki Light color palette (#FFFCF0 paper background, warm inky colors)
- Typography using Inter font for body text
- JetBrainsMono Nerd Font for code blocks
- Minimalist design philosophy inspired by analog ink on paper

**Markdown Elements**
- Headings (h1-h6) in black for strong hierarchy
- Links in cyan (#24837B), always underlined for accessibility
- Paragraphs with optimal line height (1.7)
- Bold, italic, and combined formatting
- Lists with light gray markers (#B7B5AC)
- Task lists with cyan checkboxes and strikethrough for completed items
- Blockquotes with 2px cyan left border, minimal spacing
- Horizontal rules in light gray

**Code Styling**
- Inline code in black on warm beige background
- Code blocks with 4px border-radius and subtle shadow
- Complete syntax highlighting following official Flexoki guidelines:
  - Keywords → Green (#66800B)
  - Strings → Cyan (#24837B)
  - Functions → Orange (#BC5215)
  - Numbers → Purple (#5E409D)
  - Booleans → Magenta (#A02F6F)
  - Comments → Gray (#B7B5AC, italic)
  - Variables → Blue (#205EA6)
  - Constants → Yellow (#AD8301)
  - Import/Include → Red (#AF3029)
  - Operators → Muted gray (#6F6E69)

**Tables**
- Clean, borderless design with transparent backgrounds
- Subtle gray borders (#CECDC3)
- Minimal styling for professional look

**UI Components**
- Sidebar with warm beige background (#F2F0E5)
- Search panel with proper contrast
- Footer with consistent styling
- Buttons and inputs with 4px border-radius
- Context menus and dropdowns
- Modal dialogs
- Custom cyan tooltips
- Custom scrollbar in light gray

**Advanced Features**
- Focus mode with fade effect (opacity 0.5)
- Source code mode styling
- Print/PDF export optimization
- Mermaid diagram support
- Math equation (MathJax) styling
- YAML front matter styling
- Image shadows

**Checkbox Implementation**
- Unchecked: Gray border, hover shows cyan
- Checked: Cyan background (#24837B) with white checkmark
- Properly centered using flexbox
- Vertical alignment fine-tuned with transform
- Completed tasks show strikethrough

### Documentation
- Comprehensive README.md with installation instructions for all platforms
- Quick installation guide (INSTALL.md)
- Example document (EXAMPLE.md) showcasing all features
- Font installation guides (Inter + JetBrainsMono)
- Customization tips
- Troubleshooting section
- MIT License
- This changelog

### Design Decisions
- **Black headings** instead of colored for maximum readability
- **Cyan accent color** (#24837B) for consistency throughout theme
- **Light gray list markers** (#B7B5AC) for subtle, non-distracting appearance
- **Minimal spacing** on blockquotes for compact layout
- **No table backgrounds** for clean, professional look
- **Always-underlined links** for better accessibility
- Following official Flexoki syntax highlighting guidelines from Neovim implementation

## [1.0.1] - 2024-12-24

### Fixed
- **Complete checkbox redesign** for improved reliability and consistency
  - Task list checkboxes now use inline SVG for the checkmark (more reliable than Unicode character)
  - Unchecked state: Black border with transparent background
  - Checked state: Cyan background and border with white SVG checkmark
  - Settings panel checkboxes: Use native OS rendering with `accent-color` for perfect display
  - Resolved overflow and alignment issues in both document and UI contexts
  - Improved positioning with absolute/relative layout for task lists

### Changed
- Checkbox implementation now follows best practices from Everforest theme
- Separated styling: native `accent-color` for UI, custom SVG for task lists
- More specific selectors for better compatibility (`#write li.task-list-item`)

## [Unreleased]

### Planned
- Dark mode variant (flexoki-dark.css)
- Screenshot gallery
- Additional customization examples

---

[1.0.0]: https://github.com/yourusername/flexoki-typora/releases/tag/v1.0.0
