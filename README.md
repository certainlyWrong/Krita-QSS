# Krita QSS Themes

This repository contains interface themes (QSS - Qt Style Sheets) to customize Krita's appearance using the [Style Sheet Loader Extension](https://invent.kde.org/freyalupen/style-sheet-loader-extension) plugin.

## 📦 Available Themes

The repository includes the following themes:

1. **Dracula** - Dark theme inspired by the Dracula color scheme
2. **FluentDark** - Dark theme in Microsoft Fluent Design style
3. **ReversalDark** - Dark theme with inverted color palette
4. **ViolaDarkColorScheme** - Dark theme with Viola color scheme
5. **Windows11Sunset** - Windows 11 inspired theme with sunset tones

Each theme includes:

- A `.qss` file (Qt Style Sheet) - visual styles
- A `.colors` file (KDE Color Scheme) - KDE color scheme

## 🚀 How to Use

### Prerequisites

1. **Install the Style Sheet Loader Extension Plugin**
   - Download the plugin from: https://invent.kde.org/freyalupen/style-sheet-loader-extension
   - Follow the plugin installation instructions for Krita

### Theme Installation

1. **Copy the files from the desired theme**

   - Navigate to the `themes/` folder in this repository
   - Choose the theme you want to use (for example, `Dracula.qss` and `Dracula.colors`)

2. **File location in Krita**

   - `.qss` files should be loaded through the Style Sheet Loader Extension plugin
   - `.colors` files can be installed on the KDE system (optional, for complete integration)

3. **Apply the theme in Krita**
   - Open Krita
   - Go to **Settings** → **Style Sheet Loader** (or the corresponding plugin menu)
   - Select the desired `.qss` file from the `themes/` folder
   - Restart Krita to apply the changes

### Apply Color Scheme (.colors)

For a complete experience, you can also apply the corresponding `.colors` file:

1. **On Linux (KDE Plasma)**

   - Copy the `.colors` file to `~/.local/share/color-schemes/`
   - Or use the **System Settings** → **Appearance** → **Colors** application to import

2. **Apply in Krita**
   - Go to **Settings** → **Configure Krita** → **General**
   - Select the color scheme in the appearance section

## 📁 Repository Structure

```
Krita-QSS/
├── README.md
└── themes/
    ├── Dracula.colors
    ├── Dracula.qss
    ├── FluentDark.colors
    ├── FluentDark.qss
    ├── ReversalDark.colors
    ├── ReversalDark.qss
    ├── ViolaDarkColorScheme.colors
    ├── ViolaDarkColorScheme.qss
    ├── Windows11Sunset.colors
    └── Windows11Sunset.qss
```

## 🎨 Customization

The `.qss` files can be edited to further customize the appearance. They use standard Qt Style Sheets syntax, allowing you to modify:

- Background and text colors
- Borders and rounded corners
- Button, menu, and widget styles
- Scrollbars
- And much more!

## 📝 Notes

- Some themes may not work perfectly with all versions of Krita
- It is recommended to backup your settings before applying new themes
- To disable a theme, simply remove or disable the QSS file in the Style Sheet Loader plugin

## 🔗 Useful Links

- [Style Sheet Loader Extension](https://invent.kde.org/freyalupen/style-sheet-loader-extension)
- [Qt Style Sheets Documentation](https://doc.qt.io/qt-5/stylesheet.html)
- [Krita Official Website](https://krita.org/)

## 📄 License

The themes in this repository are provided as-is. Check the original theme licenses if you plan to redistribute or modify them.

---

**Enjoy a customized interface in Krita!** 🎨
