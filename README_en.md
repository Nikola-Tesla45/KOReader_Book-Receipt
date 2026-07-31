
# 📖 KOReader Book Receipt Screensaver
[![English](https://img.shields.io/badge/English-12B7F5?style=for-the-badge&logo=github)](./README_en.md) [![简体中文](https://img.shields.io/badge/简体中文-555555?style=for-the-badge&logo=github)](./README.md)

> Turn every time you put your device to sleep into a meaningful reading ritual.

**Book Receipt Screensaver** is a custom screensaver patch for KOReader that automatically generates a clean, receipt-style reading summary whenever your device enters sleep mode. It provides an at-a-glance overview of your current book, including reading progress, chapter information, estimated time remaining, today's reading time, and more.

## 💬 Community

[![QQ Group](https://img.shields.io/badge/QQ_Group-627525507-12B7F5?logo=tencentqq)](https://qun.qq.com/universal-share/share?ac=1&authKey=%2Fta5WGRV%2BMwszV4Fk3m15RBvIsWFsiXA5YWwUdDCta519Vt8I%2BE%2FLO9wHiDfaCY9&busi_data=eyJncm91cENvZGUiOiI2Mjc1MjU1MDciLCJ0b2tlbiI6IkZSaEgzZks5dFA5am1paHhWdDdoSjFFdUdFYVk1bCtBajRpTkZRZFBFNlYzL1I3MXlOdkpkYkcwNmlVSE43UysiLCJ1aW4iOiI2MzU4MTI3MTAifQ%3D%3D&data=ippLlj9wYlBCY2YfJBVf9mWpaFzUvpZAjFKk_8ArUCvJ48ezpENOEBbb_FNZ7UuILWMG0O1yPIuHcs0aMOJMLQ&svctype=4&tempid=h5_group_info)

## ✨ Features

- 📊 **Reading Progress Overview**: Displays overall book progress, current page/total pages, and chapter progress.
- ⏱️ **Smart Time Estimation**: Automatically estimates the remaining reading time for both the current chapter and the entire book based on your reading speed.
- 📈 **Daily Reading Statistics**: Tracks today's reading time and displays the current weekday.
- 🎨 **Customizable Backgrounds**: Choose from white, black, transparent, random images, or the current book cover.
- 🖼️ **Background Image Scaling**: Fit to screen, stretch, or center.
- 🔋 **Device Status**: Shows the current battery level and time in real time.
- 🎯 **Optimized Cover Layout**: Left-aligned book cover with the date displayed on the right (Year/Month, Day, Weekday). The date is automatically hidden when using the book cover as the background.
- 🌐 **Fully Localized in Chinese**: All interface text has been translated and optimized for Chinese-speaking users.
- 🛡️ **Stable & Reliable**: Clean layout designed for consistent and reliable screensaver performance.
- 💡 **Quick Access**: Supports opening the receipt at any time via gestures or hardware buttons.

## 📸 Preview

<img width="128.0" height="182.9" alt="6144ea3d628270c365572feb9077dece" src="https://github.com/user-attachments/assets/60024b3c-06ab-41e1-8010-00deebf698bb" />
<img width="127.9" height="177.5" alt="b66d2edb99edea36948853b7c031a8c2" src="https://github.com/user-attachments/assets/4f339576-6042-4f5a-9c86-eab8d068a167" />



## 🔧 Installation

1. Copy the patch files into the `koreader/patches/` directory.
2. In KOReader, go to **Settings → Screensaver** and select **Book Receipt**.
3. Customize the background, cover scaling, and other options under **Book Receipt Settings**.

## 📋 Configuration

| Option | Description |
| ------ | ----------- |
| Background | White Fill / Transparent / Black Fill / Random Image / Book Cover |
| Background Image Placement | Fit to Screen / Stretch / Center |
| Content Mode | Book Receipt / Highlights + Progress / Random |
| Cover Scale | 0–2.0 (set to `0` to hide the cover) |

## 📝 Changelog

### v2.2 (2026.08)
- Added smart annotation/date switching: shows random highlight with vertical line when annotations exist, auto-switches to large date (2026.07 / 30 / Wednesday) when none, with smart bottom bar联动 to avoid duplicate date display
- Redesigned border with ticket/receipt style: semi-circle perforations on top/bottom, notch cutouts on left/right, subtle shadow on bottom-right; uses low-level rendering to completely eliminate crash issues
- Border now intelligently adapts to background: perforated ticket border for white/transparent backgrounds, standard square border for black/image/cover backgrounds
- Added random highlight selection: each sleep or summon may show a different annotation, with page and chapter info displayed
- Added large-date mode for no-annotation scenarios: three-line centered display (year.month / large day / weekday)
- Bottom status bar with intelligent联动: shows battery | date | time when highlights or cover background present, hides duplicate date in large-date mode

### v2.1.1 (2026.07)
- Added random highlight display: randomly picks one annotation from current book to show on screensaver top, with vertical line decoration
- Auto-falls back to large date (2026.07 / 30 / Wednesday) when no annotations exist
- Bottom status bar shows battery and time; date displayed at bottom when highlights are present
- Border thickened and darkened, radius reduced for a more receipt-like look
- Added "Content Mode" configuration: Book Receipt / Highlight+Progress / Random
- Introduced WidgetContainer:paintTo low-level drawing for much better border stability
- Added "Custom Sleep Text" feature: customize the text displayed in date position during screensaver

- ### v2.1 (2026.07)
- Added random highlight display: randomly picks one annotation from current book to show on screensaver, with vertical line decoration
- Added smart date/highlight switching: shows highlight when available, otherwise shows large date (2026.07 / 30 / Wednesday)
- Top layout optimized: cover left-aligned, date right-aligned with auto-adapting height
- Bottom status bar now syncs with top mode: shows battery | date | time when highlight or cover background is present, hides duplicate date in large-date mode
- Border thickened and darkened, radius reduced for a more receipt-like look
- Added "Content Mode" configuration: Book Receipt / Highlight+Progress / Random
- Added "Custom Sleep Text" feature: customize the text displayed in date position during screensaver
- Introduced WidgetContainer:paintTo low-level drawing for much better border stability

- ### v2.0 (2026.07)
- Full Chinese localization for all interface text
- Layout redesign: cover moved to left, date displayed on right (2026.07 / 30 / Wednesday)
- Book title now uses serif font (NotoSerif) with decorative dashes on both sides
- Progress title renamed from "Book" to "Book Progress" for clarity
- Chapter progress bar hides "Chapter" label, only displays chapter name
- Date auto-hides when background is set to "Book Cover" to avoid overlap
- Bottom status bar simplified: battery left-aligned, time right-aligned
- Added screensaver menu options: background, content mode, cover scale adjustment
- Removed unstable shadow implementation, reverted to stable borders
- Removed Emoji, replaced with dash decorations for better font compatibility

### v1.0

- Initial English release.

## 🙏 Credits

This plugin is based on the original work by Reddit user **u/hundredpercentcocoa**.

Original project: <https://github.com/omer-faruq/koreader-user-patches>

Thanks to the original author and everyone who contributed to testing and improvements.

## 📄 License

MIT License
