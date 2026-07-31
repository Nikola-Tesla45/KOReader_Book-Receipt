# 📖 KOReader 书籍收据屏保插件

> 让每一次合上设备，都成为一次阅读的仪式感。

**Book Receipt Screensaver** 是一个为 KOReader 定制的屏保补丁，在设备休眠时自动生成一张「阅读收据」，清晰展示当前书籍的阅读进度、章节信息、剩余时间、今日阅读时长等关键数据，让阅读轨迹一目了然。

## 💬 交流反馈

如有使用疑问、建议或想第一时间获取更新，欢迎加入 QQ 群交流

[![QQ Group](https://img.shields.io/badge/QQ_Group-627525507-12B7F5?logo=tencentqq)](https://qun.qq.com/universal-share/share?ac=1&authKey=%2Fta5WGRV%2BMwszV4Fk3m15RBvIsWFsiXA5YWwUdDCta519Vt8I%2BE%2FLO9wHiDfaCY9&busi_data=eyJncm91cENvZGUiOiI2Mjc1MjU1MDciLCJ0b2tlbiI6IkZSaEgzZks5dFA5am1paHhWdDdoSjFFdUdFYVk1bCtBajRpTkZRZFBFNlYzL1I3MXlOdkpkYkcwNmlVSE43UysiLCJ1aW4iOiI2MzU4MTI3MTAifQ%3D%3D&data=ippLlj9wYlBCY2YfJBVf9mWpaFzUvpZAjFKk_8ArUCvJ48ezpENOEBbb_FNZ7UuILWMG0O1yPIuHcs0aMOJMLQ&svctype=4&tempid=h5_group_info)

群号：`627525507`

## ✨ 功能特性

- 📊 **阅读进度总览**：显示书籍总进度、当前页码/总页数、章节进度
- ⏱️ **智能时间估算**：基于阅读速度自动估算剩余阅读时间（书籍/章节）
- 📈 **今日阅读统计**：自动统计今日阅读时长，并显示星期几
- 🎨 **可自定义背景**：白色/黑色/透明/随机图片/书籍封面
- 🖼️ **图片放置方式**：适应屏幕/拉伸/居中
- 🔋 **设备状态**：实时显示电池电量、当前时间
- 🎯 **封面日期联动**：封面左对齐，右侧显示日期（年月/日/星期），背景为「书籍封面」时自动隐藏日期
- 🌐 **完全中文本地化**：所有界面文字均为中文，符合中文用户习惯
- 🛡️ **稳定可靠**：简洁布局，确保屏保稳定运行
- 💡 **快捷查看**：支持手势/按键随时呼出收据


## 📸 效果预览

<img width="204.7" height="285.9" alt="22264b8cc6f92270eb5214cca61f05d5" src="https://github.com/user-attachments/assets/a7dbfff9-a120-4ae8-9b37-021d3ae1f3b6" />


## 🔧 使用方法

1. 将补丁文件放入 `koreader/patches/` 目录
2. 在 KOReader 设置 → 屏保 中选择「书籍收据」
3. 支持在「书籍收据设置」中自定义背景、封面缩放等


## 📋 配置选项

| 选项 | 说明 |
|------|------|
| 背景 | 白色填充 / 透明 / 黑色填充 / 随机图片 / 书籍封面 |
| 背景图片放置 | 适应屏幕 / 拉伸 / 居中 |
| 内容模式 | 书籍收据 / 高亮+进度 / 随机 |
| 封面缩放 | 0~2.0（设为0隐藏封面） |


## 📝 更新日志

### v2.1.1（2026.07）
- 全面汉化所有界面文字
- 布局重构：封面移至左侧，右侧显示日期（2026.07 / 30 / Wednesday）
- 书名采用衬线字体（NotoSerif），左右添加横线装饰
- 进度标题重命名：将「书籍」改为「书籍进度」，功能指向更清晰
- 章节进度条隐藏「章节」标题，仅保留章节名
- 背景为「书籍封面」时顶部日期自动隐藏，避免信息重叠
- 底部状态栏精简：电量左对齐、时间右对齐
- 新增屏保菜单选项，支持背景、内容模式、封面缩放等调节
- 移除不稳定的阴影方案，回归稳定边框
- 移除 Emoji，改用横线装饰，避免字体兼容性问题

### v1.0（原始版本）
- 初始英文版本


## 🙏 致谢与原作者

本插件基于 Reddit 用户 [u/hundredpercentcocoa](https://www.reddit.com/user/hundredpercentcocoa/) 的原创代码开发。

原始版本：[omer-faruq/koreader-user-patches](https://github.com/omer-faruq/koreader-user-patches)

感谢所有贡献者与测试者！


## 📄 许可证

MIT License
