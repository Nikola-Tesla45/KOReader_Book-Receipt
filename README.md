# 📖 KOReader Book Receipt Screensaver

[中文](./README_zh.md) | **English**

> Turn every device sleep into a reading ritual.

**Book Receipt Screensaver** is a custom screensaver patch for KOReader that automatically generates a "reading receipt" when your device goes to sleep, clearly displaying current book reading progress, chapter information, remaining time, today's reading duration, and other key data — making your reading journey visible at a glance.

## ✨ Features

- 📊 **Reading Progress Overview**: Displays total book progress, current page/total pages, chapter progress
- ⏱️ **Smart Time Estimation**: Automatically estimates remaining reading time (book/chapter) based on reading speed
- 📈 **Today's Reading Stats**: Automatically counts today's reading duration with day of the week
- 🎨 **Customizable Background**: White/Black/Transparent/Random Image/Book Cover
- 🖼️ **Image Placement**: Fit to Screen / Stretch / Center
- 🔋 **Device Status**: Real-time battery level and current time
- 🎯 **Cover & Date Sync**: Cover aligned left, date displayed on the right (Year.Month / Day / Weekday), auto-hides date when background is set to "Book Cover"
- 🌐 **Full Chinese Localization**: All interface text is in Chinese
- 🛡️ **Stable & Reliable**: Clean layout ensures stable screensaver operation
- 💡 **Quick View**: Supports gestures/keys to summon the receipt at any time

## 📸 Preview

<img width="204.7" height="285.9" alt="preview" src="https://github.com/user-attachments/assets/a7dbfff9-a120-4ae8-9b37-021d3ae1f3b6" />

## 🔧 How to Use

1. Place the patch file in `koreader/patches/`
2. Go to KOReader Settings → Screensaver → select "Book Receipt"
3. Customize background, cover scale, etc. in "Book Receipt Settings"

## 📋 Configuration Options

| Option | Description |
|--------|-------------|
| Background | White fill / Transparent / Black fill / Random image / Book cover |
| Image Placement | Fit to screen / Stretch / Center |
| Content Mode | Book receipt / Highlight+Progress / Random |
| Cover Scale | 0~2.0 (set to 0 to hide cover) |

## 📝 Changelog

### v2.1.1 (2026.07)
- Full Chinese localization
- Layout redesign: cover moved to left, date displayed on right (2026.07 / 30 / Wednesday)
- Book title uses serif font (NotoSerif) with decorative dashes on both sides
- Renamed "Book" to "Book Progress" for clarity
- Chapter progress bar hides "Chapter" label, only shows chapter name
- Date auto-hides when background is "Book Cover" to avoid overlap
- Bottom bar simplified: battery left-aligned, time right-aligned
- Added screensaver menu with background, content mode, cover scale options
- Removed unstable shadow implementation, reverted to stable borders
- Removed Emoji, replaced with dash decorations for better font compatibility

### v1.0 (Original)
- Initial English version

## 🙏 Credits

This patch is based on the original work by Reddit user [u/hundredpercentcocoa](https://www.reddit.com/user/hundredpercentcocoa/).

Original repository: [omer-faruq/koreader-user-patches](https://github.com/omer-faruq/koreader-user-patches)

Thanks to all contributors and testers!

## 📄 License

MIT License
