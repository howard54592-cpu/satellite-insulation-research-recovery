# Satellite Insulation Research Recovery

卫星绝热材料研究迭代辅助技能。负责持续优化研究流程、更新知识库。

## 功能模块

### 1. 资料索引构建
- 扫描 assets/ 文件夹中的所有文档
- 自动提炼摘要生成索引
- 维护资料关键词标签

### 2. 搜索渠道管理
- 监控各渠道成功率
- 动态调整权重
- 支持增删搜索渠道
- **配置**: [references/channels.md](references/channels.md)

### 3. Skill 说明更新
- 定时/事件触发配置
- 研究方向动态调整
- 学术关键字库管理
- **配置**: [references/keywords.md](references/keywords.md)

### 4. 版本管理
- 记录版本变更历史
- 一键切换版本
- 版本对比功能
- **配置**: [references/versions.md](references/versions.md)

## 引用配置文件

| 配置文件 | 用途 |
|----------|------|
| [references/channels.md](references/channels.md) | 搜索渠道及权重配置 |
| [references/keywords.md](references/keywords.md) | 学术关键字库及研究方向 |
| [references/versions.md](references/versions.md) | 版本历史及切换 |

## 文件结构
```
skill-name/
├── SKILL.md
├── assets/          # 生成的索引文件
├── references/     # ⬆️ 配置文件（被SKILL.md引用）
└── scripts/       # 迭代脚本
```

## 使用示例
```
@技能 执行迭代
@技能 更新索引
@技能 调整渠道权重
@技能 切换版本 v1.2.0
```

## 版本历史
- v1.0.0 (2026-03-19): 初始版本
