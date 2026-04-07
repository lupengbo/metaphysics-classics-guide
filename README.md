# metaphysics-classics-guide

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-purple)
![AgentSkills](https://img.shields.io/badge/AgentSkills-Compatible-blue)
![Standard](https://img.shields.io/badge/Standard-OpenClaw-green)

一个面向中文用户的 **传统术数经典导读 Skill**。

它不是“保证应验”的工具，而是一个更适合公开使用、学习研究、知识整理与传统术数分析辅助的技能包，重点帮助用户：

- 整理术数经典书单
- 规划阅读路径
- 解释核心术语
- 对比不同流派与典籍
- 生成适合公开传播的知识结构内容
- 按传统术数框架生成命理分析、八字/四柱分析、占卜解读、走势推演草稿

## 适用书目

- 《周易》
- 《皇极经世》
- 《黄帝阴符经》
- 《渊海子平》
- 《三命通会》
- 《子平真诠》
- 《滴天髓》
- 《葬书》
- 《地理人子须知》
- 《青囊奥语》
- 《撼龙经》
- 《梅花易数》
- 《增删卜易》
- 《万法归宗》
- 《辰州符咒大全》
- 《祝由十三科》
- 《星学大成》
- 《五行大义》

## 核心能力

- 术数经典分类整理
- 阅读顺序建议
- 单书导读
- 术语解释
- 分支体系地图
- 命理分析辅助
- 八字 / 四柱 / 命盘分析草稿
- 占卜与走势解读草稿
- 多流派对照分析
- 对外科普时的安全边界表达

## 设计原则

本技能将相关内容视作：
- 文献体系
- 思想脉络
- 术语结构
- 流派演化
- 民俗/宗教/文化研究材料

不把超自然说法当作既定事实，可以输出传统术数视角下的分析、判断和走势推演，但不提供确定性命运、医疗、法律、投资等保证。

## 适合场景

- 做玄学/术数经典入门
- 把一堆书单整理成学习路径
- 想写公开文章或做知识分享
- 想做术语索引、体系对比、研究笔记

## 不适合场景

- 保证应验式算命
- 医疗替代建议
- 符咒治病/驱邪承诺
- 承诺发财、避灾、翻盘等确定性结果
- 操控、恐吓、诈骗类用途

## 文件结构

- `SKILL.md`：主技能说明
- `references/book-map.md`：书目地图与阅读路线
- `references/safety-and-positioning.md`：安全边界与公开定位
- `references/output-templates.md`：常用输出模板
- `references/bazi-analysis-template.md`：八字 / 四柱 / 命盘分析模板
- `references/divination-analysis-template.md`：占卜分析模板
- `references/trend-forecast-template.md`：走势预测模板

## 安装教程

### 方式一：直接使用仓库源码

把本仓库放到你的 skills 目录下即可，例如：

```bash
git clone https://github.com/lupengbo/metaphysics-classics-guide.git
```

放入你自己的技能目录后，确保目录结构完整：

- `SKILL.md`
- `references/book-map.md`
- `references/safety-and-positioning.md`
- `references/output-templates.md`

### 方式二：使用 `.skill` 打包文件

如果你已经有打包好的 `.skill` 文件，可以直接导入到对应支持 Skill 的 Agent / OpenClaw 环境中。

### 使用方式

安装完成后，可直接用下面这类请求触发：

- 帮我梳理这些玄学经典的阅读顺序
- 对比《渊海子平》和《滴天髓》
- 解释一下《梅花易数》的核心思路
- 按传统术数框架分析一下这个问题
- 帮我做一份命理/走势分析草稿
- 帮我算八字
- 看一下这个四柱命盘
- 帮我排八字并做分析
- 按八字帮我看一下事业和财运
- 帮我占卜一下这个事能不能成
- 帮我看一下未来半年走势

## v1.1.0

- 增加免责声明
- 补充玄学分析与走势解读场景说明
- 增加八字 / 四柱 / 命盘分析模板
- 增加占卜分析模板
- 增加走势预测模板
- 优化公开发布时的边界表达

## Disclaimer

本技能涉及的命理、占卜、风水、走势推演等内容，均基于传统术数体系与历史文献脉络整理，仅供文化研究、学习参考、娱乐讨论与个人思考使用。

不应将其视为对现实结果的保证，也不构成医疗、法律、投资等专业建议。

## License

本项目使用 **MIT License**。
