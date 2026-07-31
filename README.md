# 📖 KOReader 阅读小票插件
[![English](https://img.shields.io/badge/English-555555?style=for-the-badge&logo=github)](./README_en.md) [![简体中文](https://img.shields.io/badge/简体中文-12B7F5?style=for-the-badge&logo=github)](./README.md)

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

<img width="128.0" height="182.9" alt="6144ea3d628270c365572feb9077dece" src="https://github.com/user-attachments/assets/cd7db596-768f-47bf-88a8-f5a4f1c64bde" />
<img width="127.9" height="177.5" alt="b66d2edb99edea36948853b7c031a8c2" src="https://github.com/user-attachments/assets/baaf8101-603b-45ba-8d89-193df1e73f0f" />



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

### v2.2（2026.08）
- 新增智能标注/日期切换：有标注时随机显示高亮内容（带竖线装饰），无标注时自动切换为大日期（2026.07 / 30 / Wednesday），底部状态栏智能联动避免日期重复
- 重构边框为票据齿孔风格：上下半圆齿孔、左右票根缺口、右下轻微阴影，采用底层绘制方案彻底解决闪退问题
- 边框根据背景智能适配：白色/透明背景启用齿孔边框，黑色/图片/封面背景自动切换为普通方框
- 新增高亮内容随机抽取，每次休眠或呼出都可能不同，显示页码和章节信息
- 新增无标注大日期模式：年月（2026.07）、超大日期数字（30）、星期几（Wednesday）三行居中显示
- 底部状态栏联动逻辑：有标注或封面背景时显示电量｜日期｜时间，无标注大日期模式下不重复显示日期

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

- ### v2.1（2026.07）
- 新增随机高亮显示：从书籍标注中随机抽取一条在屏保顶部展示，配有竖线装饰
- 新增智能日期/标注切换：有标注时显示高亮，无标注时显示大日期（2026.07 / 30 / Wednesday）
- 顶部封面与日期布局优化：封面左对齐，日期右对齐并自动适配封面高度
- 底部状态栏联动：有标注或封面背景时显示电量｜日期｜时间，无标注大日期模式下不重复显示日期
- 边框加粗并加深颜色，圆角缩小，更接近票据质感
- 新增「内容模式」配置项：书籍收据 / 高亮+进度 / 随机
- 新增「自定义休眠文字」功能：屏保时可自定义日期位置显示的文字
- 引入 WidgetContainer:paintTo 底层绘制方案，大幅提升边框稳定性

- ### v2.0（2026.07）
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
