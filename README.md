# Folio Themes

[Folio](https://github.com/XiaoWang-SXAU-Lab/folio) 学术网站编辑器的主题仓库。每个主题是一个 YAML 文件，在 Folio 的「主题」页上传即可应用，保存后整站自动换肤。

## 内置主题

| 主题 | 风格 | 文件 |
|------|------|------|
| 🌲 松林绿 | 默认，植物学感的暖纸底深绿 | [forest.yaml](themes/forest.yaml) |
| 🌊 海洋蓝 | 清爽的海洋与天空，适合计算方向 | [ocean.yaml](themes/ocean.yaml) |
| 🏛 绛红 | 暖纸底配学院绛红，古典庄重 | [crimson.yaml](themes/crimson.yaml) |
| 🌙 墨色 | 深色模式，夜读友好 | [ink.yaml](themes/ink.yaml) |

## 格式说明

```yaml
name: 我的主题          # 主题名（必填）
key: my-theme           # 标识（可选）
description: 一句话描述  # 可选
colors:
  bg: "#f5f8fa"         # 页面背景
  paper: "#ffffff"      # 卡片/纸张底色
  ink: "#1c2b36"        # 正文文字
  muted: "#5d707c"      # 次要文字
  line: "#d8e2ea"       # 边框分隔线
  primary: "#2a5d8f"    # 主色（按钮、链接、强调）
  primary_dark: "#1f4769"   # 主色悬停态
  accent: "#c07a3a"     # 点缀色（引用线、装饰图标）
  wash: "#e8f0f6"       # 浅色块背景
font_heading: "'Libre Caslon Display', Georgia, serif"   # 可选：标题字体
```

- 颜色写 `#rrggbb` 或 `#rgb`，所有字段可选，留空的项回退默认
- 欢迎提 PR 贡献新主题！

## 使用

1. 下载任意 `themes/*.yaml`
2. 打开 Folio →「主题」页 → 上传 YAML（或直接粘贴到编辑框保存）
3. 构建完成后「站点预览」查看效果；点「恢复默认」可还原
