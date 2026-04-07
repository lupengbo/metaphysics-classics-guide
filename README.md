# metaphysics-classics-guide

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-purple)
![AgentSkills](https://img.shields.io/badge/AgentSkills-Compatible-blue)
![Standard](https://img.shields.io/badge/Standard-OpenClaw-green)

面向中文用户的传统术数经典学习、玄学分析与知识整理 Skill。

它以你提供的经典书单为主要依据层，适合用于：
- 术数经典导读
- 八字 / 四柱 / 命盘分析
- 占卜解读
- 走势预测
- 风水分析
- 术语解释与流派对照

同时吸收了优秀八字技能在**触发词设计、交互式信息采集、结构化输出**上的优点，并转化为你自己的中文开源版本。

## 核心特点

- **经典依据优先**：分析时尽量回到《周易》《渊海子平》《三命通会》《子平真诠》《滴天髓》《梅花易数》《增删卜易》《葬书》等典籍脉络
- **结构化分析**：尽量按“输入信息 → 所用体系 → 推演依据 → 分析结论 → 边界提醒”输出
- **多场景覆盖**：支持导读、命理、占卜、走势、风水等方向
- **中文友好**：输入模板、触发词、输出模板都面向中文使用场景设计
- **适合公开发布**：保留必要边界说明，方便用于开源传播与复用
- **可持续迭代**：已整理同类开源项目可吸收点，并预留后续规则层 / 计算层升级空间

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
- 风水分析草稿
- 多流派对照分析
- 对外科普时的安全边界表达

## 文件结构

- `SKILL.md`：主技能说明
- `references/book-map.md`：书目地图与阅读路线
- `references/safety-and-positioning.md`：安全边界与公开定位
- `references/output-templates.md`：常用输出模板
- `references/bazi-analysis-template.md`：八字 / 四柱 / 命盘分析模板
- `references/divination-analysis-template.md`：占卜分析模板
- `references/trend-forecast-template.md`：走势预测模板
- `references/fengshui-analysis-template.md`：风水分析模板
- `references/classical-analysis-basis.md`：经典依据层整理
- `references/interactive-intake.md`：交互式信息采集建议
- `references/learning-resources.md`：学习与延伸资源
- `references/external-inspiration-map.md`：同类开源项目可吸收点整理
- `references/glossary.md`：术语库
- `references/ten-gods.md`：十神详解
- `references/mingli-rules.md`：命理规则摘要
- `references/patterns-and-structures.md`：格局与结构摘要
- `references/divination-rules.md`：占卜规则摘要
- `references/divination-question-guide.md`：占卜问法指南
- `references/fengshui-rules.md`：风水规则摘要
- `references/fengshui-scenarios.md`：风水场景指南
- `references/analysis-examples.md`：分析示例库
- `ROADMAP.md`：后续迭代路线图

## 安装教程

### 方式一：直接使用仓库源码

```bash
git clone https://github.com/lupengbo/metaphysics-classics-guide.git
```

将仓库放入你自己的 skills 目录，并确保主要文件完整保留。

### 方式二：使用 `.skill` 打包文件

如果你已经有打包好的 `.skill` 文件，可直接导入到支持 Skill 的 Agent / OpenClaw 环境中。

## 使用方式

安装完成后，可直接用下面这类请求触发：

- 帮我梳理这些玄学经典的阅读顺序
- 对比《渊海子平》和《滴天髓》
- 解释一下《梅花易数》的核心思路
- 帮我算八字
- 看一下这个四柱命盘
- 帮我排八字并做分析
- 按八字帮我看一下事业和财运
- 帮我占卜一下这个事能不能成
- 帮我看一下未来半年走势
- 帮我做一份风水分析草稿

## v1.1.0

- 增加免责声明
- 补充玄学分析与走势解读场景说明
- 增加八字 / 四柱 / 命盘分析模板
- 增加占卜分析模板
- 增加走势预测模板
- 增加风水分析模板
- 增加经典依据层整理
- 增加交互式信息采集建议
- 增加术语库
- 增加十神详解
- 增加格局与结构摘要
- 增加命理 / 占卜 / 风水规则摘要
- 增加占卜问法指南
- 增加风水场景指南
- 增加分析示例库
- 优化公开发布时的边界表达

## 免责声明

本技能涉及的命理、八字、占卜、风水、走势推演等内容，均基于传统术数体系与历史文献脉络整理，仅供文化研究、学习参考、娱乐讨论与个人思考使用。

不应将其视为对现实结果的保证，也不构成医疗、法律、投资等专业建议。

## 许可证

本项目使用 **MIT License**。
