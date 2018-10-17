---
title: Quality Assurance
localeTitle: 质量保证
---
## 质量保证

质量保证（通常称为QA）是检查开发中的产品以确保其按预期工作的方法。质量保证过程中使用的实际方法根据产品的大小和性质而有很大差异。

对于个人项目，您可能只是在进行测试，要求其他人在适当的阶段提供反馈。相比之下，银行应用程序必须对每个功能的各个方面进行详尽检查和记录，以确保其功能性和安全性。

无论质量保证流程的正式或详细程度如何，其目的都是识别错误，以便在产品发布之前解决。

### 方法

#### 敏捷

在敏捷的开发方法中，目标是每个工作周期（'sprint'）生成可以迭代添加和改进的工作软件。这使得QA流程成为开发周期的固有部分。通过在生产的每个阶段测试软件组件，可以降低发布时出现错误的风险。

### 术语

#### 自动化测试

使用预先编写的脚本完成测试，旨在控制测试的执行。

#### 黑盒子

这些测试不会在被测系统中查看，而是以与最终用户体验相同的方式将其视为“关闭”。

#### 缺陷

任何偏离应用程序的规范;通常被称为“虫子”。

#### 探索性测试

一种没有脚本的测试方法，它依赖于测试人员的独特创造力，以发现未知错误并识别回归。

#### 集成测试

一起测试各个组件/模块，以确保它们彼此连接和互动。

#### 负路径测试

一种测试方案，旨在在功能/应用程序中生成错误状态，并验证错误是否得到妥善处理。例如，在用户注册表单的电子邮件字段中输入一系列数字，并检查以确保在提供实际电子邮件地址之前不接受注册。

#### 回归测试

在新构建上完成测试，以确保新功能不会无意中破坏以前测试过的功能。

#### 烟雾测试

在进行更深入的测试之前，一种旨在确保基本功能的简约测试方法正在发挥作用。通常发生在测试过程的开始阶段。

#### 测试用例

QA测试人员/工程师提供的指定前提条件，步骤和预期结果，用于确定某个功能是否按预期执行其任务。

#### 白盒子

指在代码库内的结构级别执行的测试。程序员检查特定功能或组件的输入和输出是否为白盒测试。

也被称为'玻璃盒'，'透明盒'，'透明盒'，因为测试仪可以“看到”被测系统。

主要类别是

*   **单元测试** （单个代码单元做他们应该做的）
*   **集成测试** （单元/组件相互交互）
*   **回归测试** （在开发的后期重新应用测试以确保它们仍然有效）

有三种主要技术：

*   **等价划分** （测试的输入值代表较大的输入数据集）
*   **边界值分析** （系统使用选择的输入进行测试，其中行为和输出应该改变）
*   **因果图形** （测试是根据输入 - 输出关系的可视化设计的）

### 其他资源

[测试驱动开发（freeCodeCamp指南）](https://guide.freecodecamp.org/agile/test-driven-development)

# [单元测试（freeCodeCamp指南）](https://guide.freecodecamp.org/software-engineering/unit-tests/)

[软件测试基础](http://softwaretestingfundamentals.com/)