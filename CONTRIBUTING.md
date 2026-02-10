# Contributing to SVG-Generator

首先，感谢您考虑为本项目做出贡献！🎉

## 🤝 如何参与

### 报告 Bug

如果您发现了问题，请通过 GitHub Issues 报告：

1. 确保该问题尚未被报告
2. 创建新 Issue 并提供：
   - 清晰的问题描述
   - 复现步骤
   - 期望行为 vs 实际行为
   - 截图（如适用）
   - 环境信息（Node.js版本、操作系统等）

### 提交功能请求

有想法让 SVG-Generator 更好？我们洗耳恭听！

1. 创建 GitHub Issue
2. 使用 "Feature Request" 标签
3. 描述：
   - 您想要的功能
   - 为什么需要这个功能
   - 可能的实现方案

### 提交代码

#### 开发流程

1. **Fork 仓库**
   ```bash
   git clone https://github.com/YOUR_USERNAME/SVG-Generator.git
   cd SVG-Generator
   ```

2. **安装依赖**
   ```bash
   npm install
   ```

3. **创建分支**
   ```bash
   git checkout -b feature/amazing-feature
   # 或
   git checkout -b fix/bug-fix
   ```

4. **开发并测试**
   ```bash
   npm run dev      # 启动开发服务器
   npm run build    # 确保构建成功
   ```

5. **提交更改**
   ```bash
   git add .
   git commit -m "feat: add amazing feature"
   git push origin feature/amazing-feature
   ```

6. **创建 Pull Request**

#### 代码规范

- 使用 TypeScript 类型
- 组件使用函数式组件 + Hooks
- 添加适当的注释
- 遵循 ESLint 配置

#### 提交信息格式

```
类型: 简短描述

详细说明（可选）

Fixes #123
```

类型：
- `feat`: 新功能
- `fix`: 修复
- `docs`: 文档
- `style`: 样式调整
- `refactor`: 重构
- `test`: 测试
- `chore`: 杂项

## 🌟 贡献者

感谢所有为本项目做出贡献的人！

## 📄 许可证

本项目采用 MIT 许可证，详见 [LICENSE](./LICENSE) 文件。

---

再次感谢您的贡献！❤️
