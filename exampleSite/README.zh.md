# 祥云主题配置指南

## 简介

**祥云**，意为“吉祥的云”，是一个用于展示 MDFriday 支持的所有主题的主题。  
凭借其和谐优雅的设计，祥云非常适合以清晰且风格化的方式展示主题变体。  
无论是简单的预览还是深入的示例，祥云都能为寻求灵感和定制选项的 MDFriday 用户提供支持。

## 示例配置文件

```yaml
---
friday-plugin: enabled
site: '0'
theme: github.com/mdfriday/theme-xiang-yun
content: MDFriday/theme-xiang-yun/content
---
```

## 配置项说明

### 1. **friday-plugin**
- **描述**: 表示 MDFriday 插件的启用状态。
- **默认值**: `enabled`
- **说明**: 请保持此项设置为 `enabled`，无需修改。该字段用于标记 MDFriday 插件的启用状态，确保插件正常运行。

### 2. **site**
- **描述**: 网站 ID。
- **默认值**: `'0'`（由插件自动生成）
- **说明**: 此字段由 MDFriday 插件自动生成，用于标识您的网站 ID。建议不要更改此值。

### 3. **theme**
- **描述**: 主题的 GitHub 地址。
- **默认值**: `github.com/mdfriday/theme-xiang-yun`
- **说明**: 指定所使用 Hugo 主题的 GitHub 地址。如果需要更换为其他主题，可以修改为对应的主题地址。如果您使用的是祥云主题，请保持此值不变。

### 4. **content**
- **描述**: 内容文件夹的路径。
- **默认值**: `MDFriday/theme-xiang-yun/content`
- **说明**: 定义主题内容文件夹的位置。初始情况下，`content` 字段设置为 `empty`，插件会在用户下载示例文件后自动更新为相对路径。

## 使用建议
- 如果需要使用不同的 Hugo 主题，只需在 `theme` 字段中填写新主题的地址。
- 下载示例文件后，`content` 目录会自动更新，无需手动更改。但如果您希望指向其他文件位置，请记得更新此路径。

---

通过正确配置上述字段，您将能够成功启用祥云主题并展示内容。  
如果您有任何问题或需要进一步的帮助，请访问 MDFriday 网站的主题介绍页面：[theme-xiang-yun](https://themes.mdfriday.com/theme-xiang-yun)。