# 贡献指南

欢迎为 TRAE Community Templates 仓库做出贡献！我们感谢你的帮助，让这个资源对每个人都更好。

![TRAE Templates Banner](./assets/image/Templates.gif)

[English](./CONTRIBUTING.md) | [中文](./CONTRIBUTING.zh-CN.md)

## 📋 你可以贡献什么

我们欢迎各种类型的贡献：

1. **新项目模板** - 流行框架或技术的脚手架
2. **配置文件** - 有用的配置模板（如 `.gitignore`、`.editorconfig`）
3. **文档改进** - 更好的解释、示例或翻译
4. **Bug 修复** - 修正现有模板的问题
5. **功能建议** - 新模板类别的建议

## 🚀 如何贡献新模板

### 步骤 1：Fork 并创建分支

```bash
# Fork 本仓库
git clone https://github.com/trae-community/templates.git

# 创建新分支
git checkout -b feature/your-template-name
```

### 步骤 2：创建你的模板

#### 选择合适的类别
将你的模板放在适当的目录中：
- `templates/web-frontend/` - Web 前端项目
- `templates/backend-service/` - 后端/API 服务
- `templates/mobile-desktop/` - 移动或桌面应用
- `templates/data-ai/` - 数据科学和 AI 项目
- `templates/tools-devops/` - DevOps 和配置工具

#### 必需文件
每个模板必须包含：

1. **README.md**（必需）
   - 项目描述
   - 使用的技术栈
   - 安装/设置说明
   - 使用示例
   - 任何特殊配置说明

2. **核心模板文件**（必需）
   - 实际的代码/配置文件
   - 确保它们功能完整且经过测试

3. **.gitignore**（推荐）
   - 适合该技术的忽略规则

4. **README.zh-CN.md**（可选但鼓励）
   - README 的中文翻译

### 步骤 3：模板质量检查清单

提交前，确保你的模板：

- ✅ 开箱即用（全新测试过）
- ✅ 遵循该技术的最佳实践
- ✅ 包含清晰的设置说明
- ✅ 代码中有有意义的注释
- ✅ 使用标准的项目结构
- ✅ 不包含敏感信息（API 密钥、令牌等）
- ✅ 简洁但完整（避免不必要的复杂性）

### 步骤 4：更新主 README

在 `README.md` 的适当类别表中添加你的模板：

```markdown
| **[你的模板名称](./templates/category/your-template)** | 简短描述 | 技术栈 |
```

同时更新 `README.zh-CN.md` 的中文版本。

### 步骤 5：测试并提交

```bash
# 再次测试你的模板
# 如果适用，添加一些使用测试

# 提交你的更改
git add .
git commit -m "feat: add [template-name] template"
```

### 步骤 6：提交 Pull Request

1. 推送到你的 fork
2. 创建 Pull Request
3. 填写 PR 描述：
   - 这个模板是做什么的？
   - 为什么它有用？
   - 有什么需要审查者特别注意的吗？

## 📝 文档贡献

对于文档改进：

1. **拼写/语法错误**：直接修复，使用清晰的提交信息
2. **重大重写**：先打开 issue 讨论
3. **翻译**：创建 `README.zh-CN.md` 或改进现有翻译

## 🎯 模板指导原则

### 好模板的特征

1. **简洁但完整**
   - 只包含必要的文件
   - 展示最佳实践，而不是所有功能

2. **文档完善**
   - 解释每个文件的作用
   - 提供设置命令
   - 包含使用示例

3. **易于使用**
   - 应该在最少配置的情况下工作
   - 清晰的"快速开始"部分
   - 没有隐藏的依赖

4. **遵循约定**
   - 标准的项目结构
   - 常见的命名模式
   - 行业最佳实践

### 示例结构

```
your-template/
├── README.md              # 必需：使用说明
├── README.zh-CN.md        # 可选：中文翻译
├── .gitignore            # 推荐：Git 忽略规则
├── package.json          # 示例：包配置（Node.js）
├── src/                  # 示例：源代码
│   ├── index.js
│   └── utils.js
└── config/               # 示例：配置文件
    └── default.json
```

## 🔍 审查流程

提交 PR 后：

1. **自动化检查**：确保所有 CI 检查通过
2. **维护者审查**：维护者将在几天内审查
3. **反馈**：可能会要求你进行修改
4. **合并**：一旦批准，你的模板将被合并！

## 💡 成功提示

- **保持简单**：专注于常见用例
- **测试一切**：验证所有命令都能工作
- **积极响应**：快速回复反馈
- **向他人学习**：查看现有模板作为参考

## ❓ 有问题？

随时可以：
- 打开 issue 提问
- 加入我们的社区讨论
- 在 PR 评论中询问

## 🙏 感谢你！

你的贡献帮助世界各地的开发者更快地构建更好的应用程序。每一个贡献，无论大小，都很重要！

---

贡献愉快！🎉
