# fast-implement

编码直达实现 + 省流（省 token、提速）。当用户要「实现/落地 X / 做这个功能 / 把需求变成代码 / implement」等编码开工指令时使用。

## 安装
把 `fast-implement/` 文件夹放进技能目录：
- 用户级：`~/.workbuddy/skills/fast-implement/`（全局生效）
- 项目级：`.workbuddy/skills/fast-implement/`

## 它能做什么
- 只读完成改动必需的最小文件，不整仓扫描、不重读已读文件
- 一次一小步直达实现，只跑最窄验证
- 探查拆给轻模型子代理，强模型留作综合决策
- 长任务/长会话自动拆新代理、压缩中间产物、建议写交接+开新会话
