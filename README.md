# Swarm

[简体中文](README.zh-CN.md)

Domain Specific Language of Multi-Agent System Based on both Rules and Neural Networks

## Design Principles [设计原则](./README.zh-CN.md/#设计原则-design-principles)

The cluster mission of unmanned aerial vehicles (UAVs) can be divided into three layers:

- The **Task** layer, responsible for coordinating and scheduling multiple UAVs for collaboration and information exchange.
- The **Behavior** layer, describing the action sequences of individual UAVs.
- The **Action** layer, which describes the execution process of an atomic action of a UAV. This process is controlled by rule-based or neural network-based syntax.

## Lexcial Conventions [词法规则](./README.zh-CN.md/#词法规则-lexcial-conventions)

### Tokens [记号](./README.zh-CN.md/#记号-tokens)

- Identifiers
- Keywords
- Operators

### Identifiers [标识符](./README.zh-CN.md/#标识符-identifiers)

The naming convention requires that the name starts with a letter or underscore, and consists of letters, numbers, or underscores. It is case-sensitive.

### Keywords [关键字](./README.zh-CN.md/#关键字-keywords)

- Task, Behavior, Action
- @subtask, @behavior, @action
- @uavTypes, @topic, @init, @goal, @routine
- publish, subscribe, request, from, to
- each, order
- if, else, return

### Operators [操作符](./README.zh-CN.md/#操作符-operators)

## Grammar [语法](./README.zh-CN.md/#语法-grammar)

[EBNF](EBNF.ebnf)

## Examples [范例](./examples/zh-CN/)
To make examples in VSCode highlight as shown in the image, follow these steps:
- install plug-in [**Highlight**](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-highlight) 
- modify the setting.json of your vscode as [vscode-setting.json](./examples/zh-CN/vscode-settings.json)

![examples](./img/examples-zh-CN.PNG)