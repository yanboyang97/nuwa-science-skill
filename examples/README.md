# 12 个专业科研 skill：从一个小任务开始

[返回发行包首页](../README.md)

每个目录都包含完整的 `SKILL.md`、方法参考、`agents/openai.yaml` 和许可文件。它们可以独立安装，也可用作女娲创建或改进技能时的参考。

先选择与你当前任务匹配的例子，按 [安装说明](../README.md#quickstart) 复制完整目录，再提供真实材料并使用下方请求。请求中的技能名可直接用于自然语言；Codex CLI 或 IDE 扩展也支持用 `$技能名` 选择技能。

以下是**使用模板和检查点**，不是已经执行的演示记录。每次执行的范围、结论与未完成事项都应由实际材料决定。

## 快速导航

| 例子 | 什么时候用 |
|---|---|
| [文献调研](#literature-review) | 找到、筛选并综合与研究问题相关的文献。 |
| [文献串联](#literature-synthesis) | 把多篇研究连接成有依据的关系和发展脉络。 |
| [研究交叉评议](#research-cross-review) | 对照不同研究对具体主张的支持、冲突和互补。 |
| [科研问题发现](#research-question-discovery) | 从矛盾、解释缺口和失效边界形成可回答的问题。 |
| [研究空白与新颖性核查](#research-novelty-check) | 核对候选贡献与最接近已有工作的实质差别。 |
| [概念对齐与理论综合](#concept-theory-synthesis) | 比较术语、定义、分析层次和理论前提。 |
| [证据、方法与因果审查](#research-evidence-audit) | 审查一项研究主张能够被现有证据支持到什么程度。 |
| [假设、反例与可证伪性](#hypothesis-falsification) | 提出竞争解释，寻找有效反例，设计区分性检验。 |
| [研究方案与评价设计](#research-design) | 把问题或假设转成可执行、可检查的研究方案。 |
| [复现与结果核验](#research-reproduction) | 重算或重运行可定位的结果，并解释差异。 |
| [论证组织与学术写作](#scholarly-writing) | 把研究材料组织成可以理解、可以追溯的学术论证。 |
| [研究路线与资源取舍](#research-roadmapping) | 比较候选方向，明确优先级、阶段目标与转向条件。 |

<a id="literature-review"></a>
## 01 · 文献调研

[打开技能](literature-review/SKILL.md) · [方法依据与验证状态](literature-review/references/methods.md)

**带上：** 一个研究问题，以及已有论文、笔记或检索线索。

~~~text
请用 literature-review 围绕我提供的研究问题做一轮文献调研。先用已有材料，再补查会影响结论的缺口；交付主要研究脉络、分歧、局限和可追溯来源，说明检索范围与实际阅读范围。
~~~

**检查产物：** 关键判断是否有原文依据；检索范围、摘要线索与全文阅读是否分开。

<a id="literature-synthesis"></a>
## 02 · 文献串联

[打开技能](literature-synthesis/SKILL.md) · [方法依据与验证状态](literature-synthesis/references/methods.md)

**带上：** 一组相关研究，以及希望串联的问题或主题。

~~~text
请用 literature-synthesis 串联我提供的研究。围绕同一问题连接它们的概念、假设、方法和证据，说明每条联系的依据；区分支持、冲突、互补和目前无法连接的部分。
~~~

**检查产物：** 关系是否有两端材料与引用语境；有没有把引用、相似词语或时间先后误当成支持与继承。

<a id="research-cross-review"></a>
## 03 · 研究交叉评议

[打开技能](research-cross-review/SKILL.md) · [方法依据与验证状态](research-cross-review/references/methods.md)

**带上：** 明确的比较问题，以及至少两项相关研究或可定位线索。

~~~text
请用 research-cross-review 检查这些研究对我提供的主张是否一致。先对齐对象、条件、方法和指标，再评议支持与冲突，指出哪些差异可以解释、哪些仍待补查。
~~~

**检查产物：** 是否先核对可比性；共享数据、重复报告是否被误算成独立验证。

<a id="research-question-discovery"></a>
## 04 · 科研问题发现

[打开技能](research-question-discovery/SKILL.md) · [方法依据与验证状态](research-question-discovery/references/methods.md)

**带上：** 一个主题、现象或现实需求，以及相关研究材料。

~~~text
请用 research-question-discovery 从我提供的材料中发现值得进一步研究的问题。给出每个候选的问题表述、证据依据、知识收益、可回答路径和实施条件，不为凑数量增加候选。
~~~

**检查产物：** 问题是否来自可定位的缺口；尚未解决、新颖性和投入价值是否分别判断。

<a id="research-novelty-check"></a>
## 05 · 研究空白与新颖性核查

[打开技能](research-novelty-check/SKILL.md) · [方法依据与验证状态](research-novelty-check/references/methods.md)

**带上：** 一句具体的候选贡献，以及适用对象、条件和已有相关工作。

~~~text
请用 research-novelty-check 核查我提出的贡献。找最接近的已有工作并核对原文，分别报告已覆盖、部分覆盖、仍有差别和无法判断之处，说明版本、检索日期与覆盖限制。
~~~

**检查产物：** 是否比较实际方法和条件；没有检索到、摘要没提到，是否被误写成首次或无人研究。

<a id="concept-theory-synthesis"></a>
## 06 · 概念对齐与理论综合

[打开技能](concept-theory-synthesis/SKILL.md) · [方法依据与验证状态](concept-theory-synthesis/references/methods.md)

**带上：** 两组或多组概念或理论，以及相关原文和比较目的。

~~~text
请用 concept-theory-synthesis 比较这些研究中的概念。对齐定义、分析层次、解释对象与前提，保留同名异义和异名同义；只有证据足够时才构建综合框架，并标出不能合并的部分。
~~~

**检查产物：** 概念相似是否被误当成机制相同；新框架是否保留来源差异与待检验关系。

<a id="research-evidence-audit"></a>
## 07 · 证据、方法与因果审查

[打开技能](research-evidence-audit/SKILL.md) · [方法依据与验证状态](research-evidence-audit/references/methods.md)

**带上：** 一个具体主张及其论文、报告、数据说明或论证材料。

~~~text
请用 research-evidence-audit 审查这份材料的核心主张。核对方法、证据和论证前提，定位影响结论的偏差或缺口，给出材料目前支持的表述和最小修正建议。
~~~

**检查产物：** 是否选用适合研究类型的标准；相关、预测与因果是否混淆；无法获得数据时是否仍冒称独立重算。

<a id="hypothesis-falsification"></a>
## 08 · 假设、反例与可证伪性

[打开技能](hypothesis-falsification/SKILL.md) · [方法依据与验证状态](hypothesis-falsification/references/methods.md)

**带上：** 一个现象、主张或解释，以及已有证据。

~~~text
请用 hypothesis-falsification 检查我提出的解释。列出有意义的竞争假设，寻找有效反例，说明什么观察、推导或材料会迫使主张收窄，以及怎样区分这些解释。
~~~

**检查产物：** 反例是否命中原主张的前提；已有数据是否参与假设生成；提出检验是否被误写成验证通过。

<a id="research-design"></a>
## 09 · 研究方案与评价设计

[打开技能](research-design/SKILL.md) · [方法依据与验证状态](research-design/references/methods.md)

**带上：** 具体研究问题、已有证据，以及可用材料、时间和资源约束。

~~~text
请用 research-design 为这个问题设计一项最小可行研究。说明材料、比较条件、测量或论证方法、分析计划、判断标准和实施依赖，区分已知条件、设计假设与尚未执行的工作。
~~~

**检查产物：** 方法是否回答原问题；对照与判定标准是否明确；计划、首次执行和核验是否有清楚分工。

<a id="research-reproduction"></a>
## 10 · 复现与结果核验

[打开技能](research-reproduction/SKILL.md) · [方法依据与验证状态](research-reproduction/references/methods.md)

**带上：** 目标论文、图表或结果，以及可访问的数据、代码、协议和环境信息。

~~~text
请用 research-reproduction 核验我指定的结果。先检查可用材料和运行条件，在现有授权与资源内完成能做的步骤，保留输入、版本、参数、实际输出与差异；明确未完成部分及原因。
~~~

**检查产物：** 报告核查、原代码重运行、独立重算是否区分；实际运行记录能否支持所声称的完成范围。

<a id="scholarly-writing"></a>
## 11 · 论证组织与学术写作

[打开技能](scholarly-writing/SKILL.md) · [方法依据与验证状态](scholarly-writing/references/methods.md)

**带上：** 写作目标、读者或文体，以及草稿、证据和实际结果。

~~~text
请用 scholarly-writing 修改我提供的稿件。先核对核心主张与证据是否对应，再改善论证顺序和表达；保留实际结果的范围、未解决的问题与必要引用，不补写没有做过的实验。
~~~

**检查产物：** 重要句子能否回到证据；语言变强时依据是否同步增加；计划和推断是否被写成已经完成的结果。

<a id="research-roadmapping"></a>
## 12 · 研究路线与资源取舍

[打开技能](research-roadmapping/SKILL.md) · [方法依据与验证状态](research-roadmapping/references/methods.md)

**带上：** 研究目标、候选方向，以及已知时间、人力、材料或计算资源。

~~~text
请用 research-roadmapping 比较我提供的研究方向。分别讨论科学价值、关键不确定性、可行性和机会成本，给出条件化优先级、最小下一步以及继续、收窄或转向的条件。
~~~

**检查产物：** 资源未知是否被当作零成本；共享工作是否重复计费；优先级在关键假设变化后是否仍成立。

## 用一个例子改出自己的方法

当某个例子经常接近你的需求、却总在同一处失效，可以把真实输入、输出和具体错误交给 [女娲](../SKILL.md)，请它定位原因并调整相关规则。先复用有效部分，再验证改动后的行为。

组合使用时保留原始证据的位置、适用条件、版本和未完成状态。可参考 [能力方向与组合](../references/capability-map.md)。不必为一个小任务串联全部 12 个例子。
