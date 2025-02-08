# README

## 题目描述

你的同事问「你知不知道怎么从日程信息里抽取时间？我想用大模型帮我转换信息，输入「我下周一要去吃饭」，我期待模型能帮我把非结构化数据转换为带有 yyyy-mm-dd 格式的结构数据，但总是不准，怎么办？」

```text
这周六上午 10 点，我要在会议室 1 举行项目启动会议，讨论项目需求和目标，接着下午 2 点 30 分，在会议室 2 我有一个代码审查会议。然后在下周五上午 11 点要去上海参加一个技术论坛。
```

在这样的语境下，你看看如何开发小服务，让用户能输入非结构化的信息，输出结构化的数据。

## 题目要求

- 不使用 LangChain 等框架
- 请仔细思考数据的结构如何定义
- 请预设你要使用的模型能力，不限制使用哪种模型，但小 / 大模型有不同的技术挑战
