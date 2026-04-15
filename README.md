# 🗺️ 旅行路书生成器

> CodeBuddy Skill — 输入目的地 + 天数 + 人数，自动生成杂志级单文件 HTML 路书

## 功能特性

- 📖 杂志级排版的单文件 HTML 路书（路书 + 动线合一）
- ⏱️ 每日精确到分钟的行动动线表格
- 🎫 门票汇总 + 预约提醒
- 💰 多人分摊预算自动计算
- 🖼️ Pixabay 真实实景封面图（优先真图）
- 🎒 行前准备清单
- 📱 响应式设计，手机可看
- 🌊 滚动动画 + 视差效果

## 安装方式

### 方式一：Knot 市场安装
下载 `travel-roadbook-generator.zip`，在 CodeBuddy 中通过 Knot 上传安装。

### 方式二：手动安装
```bash
# 克隆到用户级 skill 目录
git clone https://github.com/oriri-101/travel-roadbook-generator.git ~/.workbuddy/skills/travel-roadbook-generator
```

## 使用方式

在 CodeBuddy 对话中说：
- "帮我做一个5天大理丽江的路书"
- "规划一下国庆7天西北大环线"
- "旅行规划：成都+九寨沟 4天3晚 4人"

Skill 会自动触发，按标准流程引导你完成路书生成。

## 文件结构

```
travel-roadbook-generator/
├── SKILL.md              # Skill 定义（Phase 0-5 工作流）
├── README.md             # 说明文档
└── references/
    └── template.html     # HTML 壳子模板（12 种组件）
```

## 作者

**orionxzhang**

## License

MIT
