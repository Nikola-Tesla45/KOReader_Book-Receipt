
# 📖 KOReader Book Receipt Screensaver

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

### v2.1.1 (July 2026)

- Fully localized all interface text into Chinese.
- Redesigned the layout: moved the book cover to the left and displayed the date on the right (e.g. `2026.07 / 30 / Wednesday`).
- Switched the book title to the **NotoSerif** font with decorative horizontal lines on both sides.
- Renamed the progress heading from **Book** to **Book Progress** for improved clarity.
- Removed the **Chapter** heading from the chapter progress section, leaving only the chapter title.
- Automatically hides the top date when the background is set to **Book Cover** to prevent overlapping content.
- Simplified the bottom status bar with the battery aligned left and the time aligned right.
- Added a dedicated settings menu for background selection, content mode, cover scaling, and more.
- Removed the unstable shadow rendering and reverted to a more reliable bordered design.
- Replaced emoji decorations with horizontal lines to improve font compatibility.

### v1.0

- Initial English release.

## 🙏 Credits

This plugin is based on the original work by Reddit user **u/hundredpercentcocoa**.

Original project: <https://github.com/omer-faruq/koreader-user-patches>

Thanks to the original author and everyone who contributed to testing and improvements.

## 📄 License

MIT License
