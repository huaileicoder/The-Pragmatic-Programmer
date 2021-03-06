## 注重实效的哲学

#### 你怎样去做

`提供各种选择，不是要找蹩脚的借口`-----不要说事情做不到，要说明能够做什么来挽回局面。不要害怕提出要求，也不要害怕承认你需要帮助。在你大声说出它们之前，先设法把蹩脚的借口清除出去。

`不要容忍破窗户`------如果项目中低劣的设计、错误决策、或是糟糕的设计，那就去修理，发现一个就修一个。

`做变化的催化剂`--------在有些情况下，你也许确切的知道需要什么，以及怎样去做，整个系统就在你的眼前并且你知道那是对的，但请求许可去处理整个事情，你会遇到拖延和漠然。这时候你也可以设计出你可以合理要求的东西，好好开发它。一旦完成，就拿给大家看，让他们大吃一惊，然后说：要是我们增加·····可能就会更好。假装那并不重要，坐回椅子上，等着他们开始要你增加你本来就想要的功能。人们发现，参与正在的成功要更容易，让他们瞥见未来，你就能让他们聚集在你周围。

`记住大图景`-------对自己的事情过于集中注意力，就会忘了世界的其他部分，要持续不断地观察周围发生的事情，而不只是你自己在做的事情。

*欲求更好，常把事情变糟* 

`使质量成为需求问题`-------你所制作的系统的范围和质量应该作为系统需求的一部分规定下来，如果你给用户某样东西，让他们及早使用，他们的反馈常常把你引向更好的最终解决方案。今天的了不起的软件常常比明天的完美软件更可取。

#### 经营你的资产

- 定期投资
- 多元化--你知道的事情越多，你就越有价值。你掌握的技术越多，你就能更好地进行调整，赶上变化。
- 管理风险---不要把你所有的技术鸡蛋放在一个篮子里
- 低买高卖
- 重新评估和平衡

`定期为你的知识资产投资` 

- 每年至少学习一种新语言
- 每季度/每个月阅读一本技术书籍
- 阅读非技术书籍
- 上课
- 参加本地用户组织--技术沙龙
- 试验不同的环境
- 跟上潮流---订阅商务杂志和其他期刊。选择所涵盖的技术与你当前的项目不同的刊物
- 上网

`不要就此止步`----把找到答案视为对你个人的挑战，如果你自己找不到答案，就去找出能找到答案的人。不要把问题搁在那里。所有阅读和研究都需要时间，而时间根本不够，所以你需要预先规划，让自己在空闲的时间里总有东西可读。

`批判的分析你读到的和听到的`------你需要确保你的资产中的知识都是准确的，并没有受到供应商或者媒体炒作的影响。

#### 交流

`你说什么和你怎么说同样重要`---这是交流的方面，有纸面交流，当面对话交流，首先，你要知道你想要说什么---规划出你想要说的东西，写出大纲，然后问你自己：这是否讲清了我要说的所有内容？提炼它，直到确实如此。

* 了解听众--你想让他们学到什么？她们对你讲的什么感兴趣？他们有多富有经验？他们想要多少细节？你想要让谁拥有这些信息？你如何促使他们听你说话？
* 选择风格
* 让文档美观
* 做倾听者
* 回复他人--就算现在你还没有解决问题，先回复他们你正在解决。

交流越有效，你就越有影响力。

## 注重实效的途径

#### DRY

`DRY-Dont Repeat Yourself` 

系统中的每一项知识都必须具有单一、无歧义、权威的表示。对于自己来说最基本的就是在程序中首先不要重复自己，让发现有两处是完全一样的，是不是可以把通用的地方抽出来。另外不要重复别人的，当发现有人已经做了这件事情，去看看自己是不是可以复用。与之相关的就是自己在做的时候`让复用变得容易`。在其中找到并复用已有的东西比自己编写更容易。

#### 正交性

`消除无关事物之间的影响`--总结来说就是让各部分的内容解耦，让你编写的部分做到和另一部分完全解耦或者耦合度最低。这样的组件具有：独立，具有单一、良好定义的目的。这样有两个好处：提高生产率与降低风险。

在项目中自己的工作也要和其他人解耦，不要有相关的内容。

对于注释，不要重复的介绍代码表达了什么意思，要写出为什么这样去做，代码中需要注意的点有哪些。

#### 可撤销性

*如果某个想法是你唯一的想法，再没有什么比这更危险的事情了*

`不存在最终决策`---变化很快，应该制作灵活的代码。

#### 领域语言

*语言的界限就是一个人的世界的界限*----维特根斯坦

计算机语言会影响你思考问题的方式，以及你看待交流的方式。

`靠近问题领域编程` 你应该考虑让你的项目更靠近问题编程，通过在更高的抽象层面上编码，你获得专心解决领域问题的自由，并且可以忽略琐碎的实现细节。-----why？now i cant understand

#### 估算

`估算，以避免发生意外` 首先是每个功能时间的估算，如何去估算呢，看看这个功能都可以分为几部分，每一部分你都需要多长时间去完成，并且需要加上其他不确定因素的时间。在给出估算前努力思考一下。---------关于如何估算还需要再仔细看一下书。

## 基本工具

`用纯文本保存知识` 

`利用命令shell的力量` 

`用好一种编辑器` 

#### 编辑器特性

* 可配置
* 可扩展
* 可编程

选择一种强大的编辑器，好好学习他们，减少你需要敲击的键数，设法扩展他，并将其用于比现在更多地任务。

#### 调试

`要修正问题，而不是发出指责` 

调试的思维方式，`最容易欺骗的人是自己` 

`不要恐慌`  人很容易恐慌，特别是如果你正面临最后期限的到来、或是正在设法找出bug的原因，但非常重要的事情是要后退一步，实际思考什么可能造成你认为表征了bug的那些症状。如果你目睹bug或见到bug报告时的第一反应是"那不可能"，你就完全错了。一个脑细胞都不要浪费在以“但那不可能发生”起头的死路上，因为很明显，那不仅可能，而且已经发生了。在调试的时候小心“近视”。要抵制只修正你看到的症状的急迫愿望：因为更可能的情况是，实际的故障离你正在观察的地方可能还有几步远，并且可能涉及许多其他的相关事物，要总是设法找出问题的根源，而不只是问题的特定表现。

`不要假定，要证明` 不仅是程序中的每一部分，另外策划配表，实际表现都是这样，不要假定是这样，要去证明就是这样，这样更有意义，否则就是浪费时间。程序中每一部分自己都要知道为什么这样写，这样写有什么意义，有没有其他的方式来实现。

## 解耦

`使模块之间的耦合减至最少` 

`要配置，不要集成`    `将抽象放进代码，细节放进元数据` 

#### 时间耦合

`分析工作流，以改善并发性` 

`总是为并发进行设计` 

## 编码ing

`不要靠巧合编程` 

深思熟虑的编程

- 总是意识到你在做什么
- 不要盲目的编程，不要试图构建你不完全理解的应用，或是使用自己不熟悉的技术
- 按照计划行事
- 依靠可靠地事物，不要依靠巧合或假定，如果你无法说出各种特定情形的区别，就假定是坏的
- 为你的假定设计文档
- 不要只是测试你的代码，还要测试你的假定。不要猜测，要实际尝试它。
- 为你的工作划分优先级，把时间花在重要的方面，很有可能，它们是最难的部分。
- 不要做历史的奴隶，不要让已有的代码支配将来的代码，如果不再适用，所有的代码都可被替换。

`估算你的算法的阶` 

`测试你的估算` 

#### 重构

`早重构，常重构` 

何时重构？

- 重复，当发现违反DRY的原则
- 非正交的设计
- 过时的知识
- 性能

怎么重构？

- 不要试图在重构的同时增加功能
- 在开始重构之前，确保你拥有良好的测试，尽可能经常运行这些测试
- 采取短小、深思熟虑的步骤，使自己的步骤保持短小，并在每个步骤之后进行测试，将能避免长时间的测试

## 项目开始之前

#### 挖掘需求

*完美，不是在没有什么需要增加，而是在没有什么需要去掉时达到的*

`不要搜集需求---挖掘他们` 

建立需求文档

抽象比细节活的更长久

#### 自由度

解开谜题的关键在于确定加给你各种约束，并确定你确实拥有的自由度，因为你在其中找到你的解决方案，这也是有些谜题为何如此有效的原因；你可能会太快就排除了潜在的解决方案。

`不要在盒子外面思考——要找到盒子` 在面对棘手的问题时，列出所有在你面前的可能途径，不要排除任何东西，不管它听起来有多无用或愚蠢，现在，逐一检查列表中的每一项，并解释为何不能采用某个特定的途径，你确定吗？你能证明吗？

对你的各种约束进行分类，并划定优先级

#### 准备好再开始

`倾听反复出现的疑虑——等你准备好再开始` 