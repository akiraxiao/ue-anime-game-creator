# UE Anime Game Creator Skill - 项目记忆

## 项目概述
这是一个 Unreal Engine 二次元游戏开发的 AI Skill 知识库，用于指导 AI 助手进行高质量二次元游戏开发。

## 仓库信息
- **GitHub**: https://github.com/akiraxiao/ue-anime-game-creator
- **可见性**: Public
- **主分支**: master

## 文件结构
```
├── CLAUDE.md          # 项目记忆（本文件）
├── README.md          # 项目说明
└── skill.md           # 核心 Skill 定义（~1200行）
```

## Skill 核心内容

### 1. 渲染技术 (NPR/三渲二)
- 卡通描边（后处理/反转法线/边缘检测）
- SDF 面部阴影、头发高光、边缘光
- 角色材质系统

### 2. 蓝图 & C++ 开发
- UE 核心框架
- Gameplay Ability System (GAS)
- 动画蓝图、AI 行为树
- 编辑器扩展与插件开发

### 3. 联机/多人游戏
- 网络架构（Listen Server / Dedicated Server / P2P）
- Replication 系统与 RPC
- 匹配系统、房间管理
- 在线服务集成（EOS、Steam）
- 反作弊系统

### 4. 剧情编辑器系统
#### 业界方案
| 方案 | 类型 | 价格 |
|-----|------|------|
| articy:draft | 商业 | 免费版(700对象) / €69.99/年 |
| Ink + Inkpot | 开源 | 免费 |
| Yarn Spinner | 开源 | 免费 |
| Not Yet: Dialogue System | 开源 | 免费 |

#### articy:draft 集成（已完成详细文档）
- 定价方案
- 安装步骤
- 工作流程图
- C++ / 蓝图 API
- ArticyFlowPlayer 组件
- UI 集成示例
- 本地化支持

#### 自研插件架构
- 插件模块结构（Runtime + Editor）
- 核心数据结构（StoryAsset、DialogueNode、ChoiceNode）
- 条件/动作系统
- 剧情播放器组件
- 节点图编辑器
- Sequencer 集成

### 5. 分镜系统
- Sequencer 过场动画
- 镜头语言
- 自定义对话轨道

## 技术参考
- **鸣潮 (Wuthering Waves)** - 库洛游戏 - UE 开放世界二次元
- **Blue Protocol** - Bandai Namco - UE4 动漫风 MMORPG（已停服）

## 更新历史
- 2026-02-07: 初始创建，包含蓝图/C++、渲染、联机系统
- 2026-02-07: 添加 README
- 2026-02-07: 增强剧情编辑器系统，添加业界方案对比、自研插件架构
- 2026-02-07: 添加完整 articy:draft 集成指南

## 待办事项
- [ ] 添加更多渲染技术细节（材质函数示例）
- [ ] 添加 GAS 网络同步详细示例
- [ ] 添加 Sequencer 过场动画完整工作流
- [ ] 考虑添加 Ink/Yarn Spinner 集成指南
