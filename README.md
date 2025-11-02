# MiaoYan - NetNewsWire Theme

A clean and elegant NetNewsWire theme optimized for Chinese reading experience.

![Screenshot](https://cdn.tw93.fun/pic/DnMetl.png)

## Features

### Visual Design

- Minimalist design focused on content reading
- Classic blue links with green accent color
- Circular feed avatars
- Perfect font rendering with antialiased and grayscale

### Light and Dark Themes

- Full support for macOS light/dark mode auto-switching
- Light mode: Clean and bright white background
- Dark mode: Eye-friendly dark background with optimized contrast

### Reading Experience

- Optimized Chinese typography with 0.5px letter-spacing and 1.7 line-height
- Compact layout with article titles linking directly to original content
- Smooth transitions for all links and interactive elements
- Responsive design for different screen sizes

### Detail Refinements

- Gray blockquote borders
- Rounded corners for code blocks and images
- Optimized list and table styling
- Print-friendly styles

## Installation

### Method 1: One-Click Install (Recommended)

Click this link to install directly:

```
netnewswire://theme/add?url=https://github.com/tw93/MiaoYan-NetNewsWire-Theme/releases/latest/download/MiaoYan.nnwtheme.zip
```

Or visit the [releases page](https://github.com/tw93/MiaoYan-NetNewsWire-Theme/releases) and download the latest version.

### Method 2: Manual Installation

1. Download `MiaoYan.nnwtheme.zip` from [releases](https://github.com/tw93/MiaoYan-NetNewsWire-Theme/releases)
2. Unzip the file
3. Open Finder and press `Cmd + Shift + G`, then enter:

   ```
   ~/Library/Containers/com.ranchero.NetNewsWire-Evergreen/Data/Library/Application Support/NetNewsWire/Themes/
   ```

4. Copy `MiaoYan.nnwtheme` to this directory
5. Restart NetNewsWire
6. Select MiaoYan theme in NetNewsWire preferences

### Method 3: Via Git

```bash
cd ~/Library/Containers/com.ranchero.NetNewsWire-Evergreen/Data/Library/Application\ Support/NetNewsWire/Themes/
git clone https://github.com/tw93/MiaoYan-NetNewsWire-Theme.git MiaoYan.nnwtheme
```

## Color Scheme

### Light Mode

- Links: `#0066CC` (Classic Blue)
- Accent: `#39583E` (Deep Green)
- Text: `#444444`
- Background: `#FDFDFD`

### Dark Mode

- Links: `#6CB4EE` (Light Blue)
- Accent: `#7FA884` (Light Green)
- Text: `#DCDCDC`
- Background: `#1A1A1A`

## Fonts

Primary font is TsangerJinKai02 with fallbacks to system fonts:

- macOS: PingFang SC
- Windows: Microsoft YaHei
- Code: SF Mono

The theme uses local fonts first, and falls back to web fonts from CDN if local fonts are not available.

## Compatibility

- NetNewsWire 6.0+
- macOS 11.0+
- iOS/iPadOS supported (via NetNewsWire iOS version)

## Changelog

### v1.0.0 (2025-10-30)

- Initial release
- Complete light/dark theme support
- Optimized Chinese typography
- Circular feed avatars
- Clean layout design

## Author

**Tw93**

- Website: [https://tw93.fun/](https://tw93.fun/)
- GitHub: [@tw93](https://github.com/tw93)

## License

MIT License

## Acknowledgments

Thanks to the NetNewsWire team for creating an excellent RSS reader.
