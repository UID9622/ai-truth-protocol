# 致所有AI用户：如何避免被"伪代码"误导

[![License](https://img.shields.io/badge/license-MulanPSL%20v2%20%7C%20CC%20BY--NC--SA%204.0-green)](LICENSE)[![Stars](https://img.shields.io/github/stars/UID9622/ai-truth-protocol?style=social)](https://github.com/UID9622/ai-truth-protocol/stargazers)[![Issues](https://img.shields.io/github/issues/UID9622/ai-truth-protocol)](https://github.com/UID9622/ai-truth-protocol/issues)[![Last Commit](https://img.shields.io/github/last-commit/UID9622/ai-truth-protocol)](https://github.com/UID9622/ai-truth-protocol/commits)

**作者：** Lucky | UID9622  
**GPG指纹：** A2D0092CEE2E5BA87035600924C3704A8CC26D5F

## 问题

AI（Claude、ChatGPT、DeepSeek等）生成的代码：
- 70%是"伪代码"（不能直接运行）
- 20%是"示例代码"（需要修改）
- 10%是"真代码"（可以直接用）

但AI不会告诉你。

## 解决方案

### AI输出标注协议

每次AI输出代码时，应该标注：
```markdown
## 🏷️ AI输出类型声明

**输出者：** [AI名称]
**输出类型：** [架构伪代码/生产级代码/示例代码]
**可执行性：** [❌不可直接执行 / ⚠️需要适配 / ✅可直接执行]
**依赖环境：** [具体环境]
**关键提示：** [注意事项]
```

### 使用方法

问AI时加一句：
```
"请用标注协议回复"
```

## 完整文档

详见仓库文件。

## 联系方式

- **GPG指纹：** A2D0092CEE2E5BA87035600924C3704A8CC26D5F
- **Signal：** UID9622.20120813
- **QQ：** 346045695

## 开源协议

MIT License\n\n---\n\n## 🐉 龙魂生态验证入口\n\n本仓库已完成龙魂生态对齐验证。\n\n- [身份锚点](./LONGHUN_VERIFICATION.md)\n- [对齐证明](./LONGHUN_ALIGNMENT_PROOF.md)\n- [龙魂系统主仓](https://github.com/UID9622/longhun-system)\n\n**生态状态:** 🟢 已验证 | **对齐标准:** v1.0\n