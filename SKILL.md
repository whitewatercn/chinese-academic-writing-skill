---
name: chinese-academic-writing
description: Refine Chinese academic manuscripts by removing translationese, formulaic AI phrasing, excessive logical connectors, and nominalization while preserving facts, citations, terminology, and scholarly rigor. Especially useful for medical and traditional Chinese medicine writing.
---

# 中文学术写作优化 / Chinese Academic Writing

## 适用场景 / When to use

当用户要求润色、改写、去翻译腔、去 AI 味或提升中文论文自然度时使用。适用于中文学术论文、医学论文及中医学术论述；不适用于用户明确要求翻译或改变论点的任务。

Use when the user requests polishing or rewriting Chinese scholarly prose to improve idiomatic expression. Do not treat this as translation or substantive peer review.

## 工作流程 / Workflow

1. 识别文本的学科、文体、核心论点、专业术语、引文、数据及参考文献标记。
2. 检查翻译腔：冗余逻辑连接词、抽象名词堆叠、英语式名词化、被动表达、机械对称句和无信息量的总结句。
3. 逐段改写：优先使用准确、简洁、自然的现代书面汉语；必要时调整语序、合并重复内容、拆分过长句子。
4. 保留论证强度：不得把“可能”“相关”改成“必然”“导致”；不得补充未经原文支持的机制或结论。
5. 核对引文、数字、参考文献标记、专业术语和标题层级；经典原文保持原样，发现疑似错误时标注待核，不擅自改写。
6. 默认仅输出改写稿；如用户要求，再给出修改说明或对照表。

## 编辑准则 / Editing rules

- 不机械保留“由此、因此、从而、进而、值得注意的是”等连接词；但逻辑需要时应保留。
- 减少“实现对……的改善”“对……产生影响”“体现了……之间的相互关系”等冗余表达，改为具体谓语或直接描述关系。
- 避免反复套用“通过……实现……”“不仅……而且……”“既是……也是……”“为……提供理论依据”等模板；不是全面禁用。
- 删除无新增信息的复述与空泛总结，不删除必要的限定条件、证据或推理步骤。
- 中医语境使用规范术语，如“气血失调”“筋脉失养”；不生造术语、不刻意文言化。
- 区分“经典原文所载”与“作者据此推论”，不把解释性推断写成经典原意。
- 保持学术准确性、原文观点、引用和数据；不得虚构参考文献。

## 输出约定 / Output

默认直接输出润色后的完整中文文本，保留原文段落结构和引用标记；不添加无关前言。若原文存在事实或引文疑点，在正文之外简要列出“待核实事项”，不擅自修正。用户要求对照时，输出“原文 / 修改后 / 修改理由”。

## 示例 / Example

原文：由此，气机郁滞可经气机与气血运行失常而累及筋脉形体，体现气与形相互影响。

改写：气血运行失常，筋脉失于濡养，可见拘急或弛缓等表现，反映了气血失调与筋脉病变的密切关系。

注意：示例只展示语言风格，不意味着两句医学含义完全等价。实际改写必须根据上下文保留原文具体病机与证据强度。
