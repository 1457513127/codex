# 项目更新日志

此文件是 Notion 暂不可写时的可靠落盘记录。Notion 项目更新文档建立后，每条记录都应同步并填写页面链接。

## 2026-05-26 - 建立持续协作与视觉一致性基线

状态：已同步 Notion

目标：把长期上下文、小范围迭代、Airbnb inspired 设计系统使用及更新记录要求变成项目内固定流程。

改动：

- 新增 `AGENTS.md`，规定新会话读取顺序、变更预算、设计与 Notion 约束。
- 新增 `docs/PROJECT_MEMORY.md` 与 `docs/CHANGE_POLICY.md`，承接稳定记忆和小改协议。
- 新增 `design-system/README.md` 与 `design-system/airbnb-tokens.css`，建立统一视觉 token 来源。
- 将唯一现有演示界面接入共享 token 文件，不变更页面流程和业务内容。

验证：

- 已完成：检查 HTML 对共享 `airbnb-tokens.css` 的引用及原型静态资源路径。
- 已完成：扫描演示 HTML，未发现绕过共享 token 的硬编码颜色、阴影或字体栈。
- 已完成：通过本地预览打开原型并切换到“活动详情与披露”，确认样式表已加载且主办方/推荐团长信息仍正常展示。

Notion 同步：

- 已写入 [和趣亲子活动平台 - 产品与代码更新日志](https://www.notion.so/36c9f99b7c3980d2a516fe864dfd780d)。
- GitHub 发布完成后，将最终提交链接追加到 Notion 记录中。
