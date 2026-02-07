# UE Anime Game Creator Skill

Unreal Engine 二次元游戏开发 AI Skill - 专为 Claude Code / AI 助手设计的专业知识库

## 概述

这是一个专门用于指导 AI 助手开发高质量 Unreal Engine 二次元（Anime-style）游戏的 Skill 文件。涵盖从渲染技术到联机系统的完整技术栈。

## 核心能力

### 渲染技术 (NPR/Cel-Shading)
- 三渲二渲染管线设计
- 卡通描边（后处理/反转法线/边缘检测）
- SDF 面部阴影、头发高光、边缘光
- 角色材质（皮肤、头发、眼睛、服装）
- 自定义着色模型

### 蓝图 & C++ 开发
- UE 核心框架（Actor、Component、GameMode）
- Gameplay Ability System (GAS)
- 动画蓝图与状态机
- AI 行为树
- 编辑器扩展与插件开发

### 联机/多人游戏
- 网络架构（Listen Server / Dedicated Server / P2P）
- Replication 系统与 RPC
- 客户端预测与服务器校正
- 匹配系统与房间管理
- 在线服务集成（EOS、Steam、PSN、Xbox Live）
- 反作弊系统

### 剧情编辑器系统

#### 业界方案对比
| 方案 | 类型 | 价格 | 适用场景 |
|-----|------|------|---------|
| [articy:draft](https://www.articy.com/) | 商业 | 免费版(700对象) / €69.99/年 | 大型项目、专业叙事团队 |
| [Ink + Inkpot](https://github.com/The-Chinese-Room/Inkpot) | 开源 | 免费 | 文字冒险、分支叙事 |
| [Yarn Spinner](https://yarnspinner.dev/) | 开源 | 免费 | 独立游戏、快速原型 |
| [Not Yet: Dialogue System](https://github.com/NotYetGames/DlgSystem) | 开源 | 免费 | 中小型项目 |
| [Narrative Tales](https://www.fab.com/) | 商业 | 付费 | RPG、开放世界 |

#### articy:draft 集成（推荐大型项目）
Skill 包含完整的 articy:draft UE 集成指南：
- 定价方案对比
- 安装步骤（软件 + UE 插件）
- 完整工作流程图
- C++ / 蓝图 API 使用示例
- ArticyFlowPlayer 组件详解
- UI 集成示例
- 本地化支持

#### 自研插件架构
Skill 包含完整的自研剧情编辑器插件设计：
- 可视化节点图编辑器
- 对话/选项/条件/动作节点系统
- 剧情播放器组件
- Sequencer 过场动画集成
- 本地化支持
- 预览与调试工具

### 分镜系统
- Sequencer 过场动画架构
- 镜头语言（景别、运动、构图）
- 自定义对话轨道
- 分镜数据结构

## 技术参考

### UE 二次元游戏案例
- **鸣潮 (Wuthering Waves)** - 库洛游戏 - [开发者访谈](https://www.unrealengine.com/en-US/developer-interviews/exploring-the-post-apocalyptic-charm-of-asg-open-worlds-in-wuthering-waves)
- **Blue Protocol** - Bandai Namco - UE4 动漫风 MMORPG

## 使用方法

### Claude Code
将 `skill.md` 内容作为系统提示或上下文提供给 Claude。

### 其他 AI 助手
可以将此 Skill 文件导入支持自定义知识库的 AI 工具中。

## 文件结构

```
├── README.md          # 本文件
└── skill.md           # 完整 Skill 定义（核心文件）
```

## 适用场景

- 二次元/动漫风格游戏开发
- 开放世界 RPG
- 视觉小说 / Galgame
- 多人在线游戏
- 需要复杂剧情系统的项目

## 贡献

欢迎提交 Issue 和 Pull Request 来完善这个 Skill。

## 许可

MIT License

## 相关资源

- [Unreal Engine 文档](https://docs.unrealengine.com/)
- [articy:draft UE 集成](https://www.articy.com/en/downloads/unreal/)
- [Inkpot - Ink UE5 插件](https://github.com/The-Chinese-Room/Inkpot)
- [Not Yet: Dialogue System](https://github.com/NotYetGames/DlgSystem)
- [Yarn Spinner](https://yarnspinner.dev/)
