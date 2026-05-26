# Airbnb Inspired 界面基线

## 来源

所有界面以 VoltAgent `awesome-design-md` 中的 [Airbnb inspired DESIGN.md](https://github.com/VoltAgent/awesome-design-md/blob/main/design-md/airbnb/DESIGN.md) 为设计依据。该来源描述的是受 Airbnb 启发的分析系统，不代表本项目使用 Airbnb 官方资产或授权字体。

## 项目执行规则

- 唯一主操作色为 Rausch `#ff385c`，用于主按钮、选中入口和关键行动反馈。
- 页面以白色画布、近黑文字和浅灰分隔线为基础，避免新增竞争性的品牌色。
- 卡片使用图片主导布局和柔和圆角；交互使用共享的单层轻阴影。
- 字体优先采用可用的系统字体栈；不打包或声称拥有 `Airbnb Cereal VF` 字体文件。
- 所有页面必须引用 `airbnb-tokens.css`，在组件样式中通过 CSS variables 使用颜色、圆角、间距、字体和阴影。

## 核心映射

| 范畴 | Token/值 | 用途 |
| --- | --- | --- |
| 主色 | `--color-action` / `#ff385c` | 主 CTA、选中态 |
| 深色文字 | `--color-ink` / `#222222` | 标题、正文 |
| 次要文字 | `--color-muted` / `#6a6a6a` | 辅助信息 |
| 画布 | `--color-canvas` / `#ffffff` | 页面及卡片 |
| 弱表面 | `--color-surface-soft` / `#f7f7f7` | 轻提示、选项底色 |
| 边框 | `--color-hairline` / `#dddddd` | 分隔与轮廓 |
| 圆角 | `--radius-sm/md/full` | 按钮、卡片、胶囊 |

## 新界面检查

1. 页面已引用 `../design-system/airbnb-tokens.css` 或等价路径。
2. 主按钮仅使用 `--color-action`/`--color-action-active`。
3. 样式中未新增未经说明的十六进制颜色、阴影或字体栈。
4. 设计 token 的新增或变更已写入 `docs/UPDATE_LOG.md` 并同步 Notion。
