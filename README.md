# AI 智能学习 · 飞牛 NAS 版

将 [思源「AI 智能学习」插件](https://github.com/YYK0402/AIstudy) 的功能一比一复刻为飞牛 NAS 应用，目标上架飞牛应用中心。

## 功能

- 课程 / 资料 / 知识点管理（PDF / Word / PPT / TXT / MD 解析）
- AI 出题、费曼学习对话、选择题练习
- SM-2 间隔重复复习调度
- 知识图谱、掌握度报告、学习计划甘特图
- 自定义 OpenAI 兼容模型、课程包导入导出

## 架构（规划中）

```
web/      Vue 3 SPA（自 AIstudy 移植，桥接层改为 HTTP 适配器）
server/   Node 服务端：数据持久化、AI 代理、Markdown 落库、OCR
```

## 状态

规划阶段。实施计划见仓库 issue / 开发记录。
