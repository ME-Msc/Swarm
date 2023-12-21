# Swarm

[English](./README.md)

基于规则和神经网络的多智能体系统领域特定语言

## 设计原则 [Design Principles](./README.md/#design-principles)

无人机集群任务可分为三个层级关系

- 多机任务**Task**层，负责调度多架无人机如何协同配合、信息交换
- 单机行为**Behavior**层，负责描述单一无人机的动作序列
- 单一动作**Action**层，描述无人机的一个原子动作的执行过程，该过程由基于规则或基于神经网络的语法进行控制

## 词法规则 [Lexcial Conventions](./README.md/#lexcial-conventions)

### 记号 [Tokens](./README.md/#tokens)

- 标识符 Identifiers
- 关键字 Keywords
- 操作符 Operators

### 标识符 [Identifiers](./README.md/#identifiers)

以字母或下划线开始，由字母、数字或下划线构成，大小写敏感。

### 关键字 [Keywords](./README.md/#keywords)

- Task, Behavior, Action
- @subtask, @behavior, @action
- @uavTypes, @topic, @init, @goal, @routine
- publish, subscribe, request, from, to
- each, order
- if, else, return

### 操作符 [Operators](./README.md/#operators)

## 语法 [Grammar](./README.md/#grammar)

[EBNF](EBNF.ebnf)

## 范例 [Examples](./examples)

按下述步骤让范例在vscode如下图一样高亮显示

- 安装插件 [**Highlight**](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-highlight)
- 按照[vscode-setting.json](./examples/zh-CN/vscode-settings.json)修改你的vscode中的配置文件setting.json

![examples](./img/examples-zh-CN.PNG)