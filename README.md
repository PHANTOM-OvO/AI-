# Auto-CodeGuard: AI-Driven Multi-Agent Code Review System

## 🚀 项目概述
Auto-CodeGuard 是一个基于 **LangGraph** 构建的多智能体（Multi-Agent）系统，旨在自动化识别代码漏洞并生成修复补丁。

### 核心价值（解决痛点）
1. **深度漏洞检测**：超越简单的语法检查，利用大模型的**长链推理**追踪跨文件逻辑漏洞。
2. **自动化闭环**：通过 **Reviewer -> Fixer -> Verifier** 的协作流，实现发现、修复、验证的无人值守闭环。

## 🛠️ 核心架构
本项目包含两个关键角色：
- **Reviewer Agent**: 模拟安全专家进行深度扫描，输出结构化报告。
- **Fixer Agent**: 根据报告和上下文，自动生成修复代码。

## 📦 安装与运行
1. **安装依赖**:
   ```bash
   pip install -r requirements.txt
