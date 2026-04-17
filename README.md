# AI Hub 数据仓库

本仓库存储 [AI Hub](https://github.com/snipercai/Showcase) 应用的所有数据，采用 Markdown 格式。

## 📁 目录结构

```
ai-hub-data/
├── README.md              # 本文件
├── version.json           # 数据版本信息
├── news/                  # 行业资讯
│   └── index.md
├── tools/                 # AI 工具
│   └── index.md
├── prompts/               # 提示词
│   └── index.md
├── projects/              # 项目案例
│   └── index.md
├── resources/             # 学习资源
│   └── index.md
└── learning-journals/     # 学习记录
    └── index.md
```

## 📝 数据格式

所有数据采用 Markdown 格式，包含：
- **Front Matter**: 元数据（标题、分类、标签等）
- **正文内容**: 人类可读的 Markdown 内容
- **嵌入 JSON**: 便于程序解析的结构化数据

## 🔄 数据同步

AI Hub 应用会在：
1. **首次启动**: 自动从本仓库拉取最新数据
2. **手动同步**: 用户可手动触发数据更新
3. **本地缓存**: 数据缓存在 localStorage，支持离线使用

## 📊 当前数据统计

| 数据类型 | 数量 |
|---------|------|
| 行业资讯 | 2    |
| AI 工具 | 2    |
| 提示词 | 2    |
| 项目案例 | 2    |
| 学习资源 | 2    |
| 学习记录 | 3    |

## 🤝 贡献

欢迎通过 Issue 或 Pull Request 贡献数据！

## 📄 许可证

MIT License
