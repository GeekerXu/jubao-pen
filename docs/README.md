# 聚宝盆文档索引

> 所有文档的导航中心

## 📚 文档分类

### 核心文档

| 文档 | 说明 | 位置 |
|------|------|------|
| README.md | 项目介绍和快速开始 | [/README.md](../README.md) |
| CONTRIBUTING.md | 贡献指南 | [/CONTRIBUTING.md](../CONTRIBUTING.md) |
| LICENSE | 开源协议 | [/LICENSE](../LICENSE) |

### 项目计划

| 文档 | 说明 | 位置 |
|------|------|------|
| 项目总览 | 100 个项目计划概览 | [/plans/](../plans/) |
| 详细计划 | 单个项目的详细规划 | [/plans/detailed/](../plans/detailed/) |

### 调研资料

| 文档 | 说明 | 位置 |
|------|------|------|
| 调研目录 | 所有调研资料索引 | [/research/](../research/) |

### 技术文档

| 文档 | 说明 | 位置 |
|------|------|------|
| 部署指南 | GitHub Pages 部署说明 | [查看](#部署指南) |
| 开发规范 | 代码和文档规范 | [查看](#开发规范) |

## 🗺️ 使用指南

### 新用户

1. 从 [README.md](../README.md) 开始，了解项目概况
2. 浏览项目计划，了解 100 个项目主题
3. 查看已完成的 HTML 页面

### 贡献者

1. 阅读 [CONTRIBUTING.md](../CONTRIBUTING.md) 了解贡献流程
2. 查看开发规范
3. 选择一个项目开始贡献

### 研究者

1. 查看 `research/` 目录的调研资料
2. 参考项目计划中的研究方向
3. 提交新的调研成果

## 📖 部署指南

### GitHub Pages 自动部署

本项目配置了 GitHub Actions，每次推送到 `main` 分支时自动部署 HTML 页面到 GitHub Pages。

**访问地址**: `https://your-username.github.io/jubao-pen/`

### 本地预览

```bash
# 使用 Python 内置服务器
cd html
python -m http.server 8000

# 访问 http://localhost:8000
```

## 📝 开发规范

### 文档规范

- 使用 Markdown 格式
- 中文内容使用简体中文
- 代码块标注语言类型
- 保持标题层级清晰

### 文件命名

- 小写字母
- 连字符分隔：`my-file.md`
- 避免空格和特殊字符

### Git 提交规范

```
feat: 新功能
fix: 修复问题
docs: 文档更新
style: 格式调整
refactor: 重构
test: 测试相关
chore: 构建/工具
```

## 🔗 相关链接

- [项目主页](../README.md)
- [贡献指南](../CONTRIBUTING.md)
- [GitHub 仓库](https://github.com/your-username/jubao-pen)

---

**最后更新**: 2026-03-03
