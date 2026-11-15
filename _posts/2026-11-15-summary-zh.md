---
layout: default
title: "Horizon Summary: 2026-11-15 (ZH)"
date: 2026-11-15
lang: zh
---

> From 17 items, 12 important content pieces were selected

---

1. [博客主张所有 AI 生成的代码都应开源](#item-1) ⭐️ 8.0/10
2. [MacBook Pro OLED 屏幕采用低频 PWM 调光，引发闪烁担忧](#item-2) ⭐️ 7.0/10
3. [微软 365 服务中断导致 15 名酒店客人氯气中毒](#item-3) ⭐️ 7.0/10
4. [Sebastian Raschka 解释现代 LLM 中的位置嵌入](#item-4) ⭐️ 7.0/10
5. [对 8900 笔众议员股票交易的分析发现中位数交易未能跑赢市场](#item-5) ⭐️ 7.0/10
6. [乌鸦决策速度超越人类，挑战“鸟脑”偏见](#item-6) ⭐️ 6.0/10
7. [Turbo Pascal 的微小体积引发对现代软件膨胀的讨论](#item-7) ⭐️ 6.0/10
8. [Emacs 作为浏览器：基于文本的网络实验](#item-8) ⭐️ 6.0/10
9. [法院驳回 DRAM 价格操纵案撤诉动议](#item-9) ⭐️ 6.0/10
10. [阿波罗任务携带榴弹发射器用于地震实验](#item-10) ⭐️ 6.0/10
11. [开发者展示用 Odin 编写的 NES 模拟器](#item-11) ⭐️ 6.0/10
12. [datasette-llm 0.1a11 新增对 OpenAI 兼容端点的支持](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [博客主张所有 AI 生成的代码都应开源](https://jakub.jankiewicz.org/blog/ai-code-open-source/) ⭐️ 8.0/10

Jakub Jankiewicz 的一篇博客文章主张所有 AI 生成的代码都应开源，在 Hacker News 上引发了 989 分、549 条评论的热烈讨论。 这场辩论之所以重要，是因为 AI 编程工具已无处不在，而 AI 生成的代码能否享有版权或必须开源，直接影响开发者、企业以及整个开源生态。 讨论中引用了美国版权局的指导意见，指出只要人类创造性贡献足够显著，AI 辅助产出的作品仍可享有版权；评论者还指出开源许可证依赖于版权，因此缺乏版权的代码可能根本无法授权。

hackernews · jcubic · Nov 15, 14:46 · [社区讨论](https://news.ycombinator.com/item?id=50507303)

**背景**: GPL、AGPL 等开源许可证依赖版权法来执行其条款，因此如果 AI 生成的代码不具备可版权性，就可能无法适用这些许可证。与此同时，AI 模型通常基于公开的开源代码训练，引发了关于署名和许可证合规的担忧。美国版权局已发布指导意见，认为现有法律可以处理 AI 相关的版权问题，但该问题在法律上仍无定论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://allthingsopen.org/articles/copyright-problem-ai-generated-code-open-source-licenses">The copyright problem with AI-generated code | We Love Open ...</a></li>
<li><a href="https://www.techtarget.com/searchEnterpriseAI/tip/Examining-the-future-of-AI-and-open-source-software">Does AI-generated code violate open source licenses?</a></li>

</ul>
</details>

**社区讨论**: 评论者意见分歧：一些人认为 AI 只是像编译器一样的工具，人类的指导足以构成所有权依据；另一些人则指出 AI 本身基于开源代码训练，质疑只对 AI 产出强制开源的逻辑一致性。一位 AGPL 系统的作者分享了一个具体案例：某公司先盗用其代码，随后用 LLM 克隆该系统，凸显了现实中的许可证冲突。

**标签**: `#AI`, `#open-source`, `#copyright`, `#software-engineering`, `#licensing`

---

<a id="item-2"></a>
## [MacBook Pro OLED 屏幕采用低频 PWM 调光，引发闪烁担忧](https://macanorak.com/the-macbook-pros-oled-pwm-problem-when-a-better-display-becomes-worse-to-use/) ⭐️ 7.0/10

MacAnorak 上发表的一篇分析指出，新款 MacBook Pro 的 OLED 显示屏采用频率低至 240 Hz 的 PWM 调光，可能对敏感用户造成闪烁相关的不适。该文章在 Hacker News 上引发了 195 条评论的热烈讨论，评论者就实际 PWM 频率展开辩论，并分享了个人对闪烁敏感的经历。 这很重要，因为显示质量不仅关乎色彩和亮度，还关乎人体工学；低频 PWM 闪烁可能使部分用户出现眼睛疲劳、头痛和头晕，从而让原本更优秀的屏幕对他们来说反而更难使用。这也引发了对苹果设计选择的质疑，并可能影响未来的显示标准和用户认知。 根据引用的实验室测试，配备新型串联 OLED 面板的 14 英寸 MacBook Pro 在亮度为 99% 或更低时使用 240 Hz PWM 调光，闪烁深度约为 56%。相比之下，之前的 Mini-LED 型号测得约 14,880 Hz，这意味着新 OLED 的调制频率大约低了 62 倍，不过一些评论者认为由于串联层相位偏移，有效频率可能更高。

hackernews · MacAnorak · Nov 15, 13:15 · [社区讨论](https://news.ycombinator.com/item?id=50506719)

**背景**: OLED 显示屏没有背光；相反，每个像素自行发光。为了调暗屏幕，大多数 OLED 使用脉冲宽度调制（PWM），即快速开关像素。这种开关的频率（以赫兹为单位）和调制深度决定了闪烁是否可被感知。虽然许多人不受影响，但少数人对低频闪烁敏感，会出现眼睛疲劳和头痛等症状。这个问题在智能手机中已被广泛讨论，现在正成为 OLED 笔记本电脑的一个关注点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.appleheadlines.com/macbook-pro-oled-eye-strain-pwm-flicker/">MacBook Pro OLED Eye Strain & PWM Flicker: 7 Moves - AH</a></li>
<li><a href="https://macbreeze.com/proled-macbook-pro-pwm-dimming-eye-strain/">PROLED MacBook Pro Users Report Eye Strain Driven by Low ...</a></li>
<li><a href="https://circadianshield.com/guides/oled-pwm-flicker-eye-strain/">OLED PWM Dimming and Eye Strain: Why OLED Screens Flicker</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论内容丰富且技术性强。一些评论者质疑 240 Hz 这一数字，认为由于相位偏移层，串联 OLED 可能有效运行在 480 Hz 甚至 960 Hz；而其他人则分享了个人对闪烁敏感的经历，包括脑震荡相关症状以及对 CRI 和运动模糊等其他显示因素的敏感。人们普遍担心苹果会发布 PWM 频率如此低的显示屏，并分享了关于人类闪烁感知的研究链接。

**标签**: `#OLED`, `#PWM flicker`, `#display technology`, `#hardware ergonomics`, `#MacBook Pro`

---

<a id="item-3"></a>
## [微软 365 服务中断导致 15 名酒店客人氯气中毒](https://www1.wdr.de/nrw/rheinland/rhein-erft-kreis/technischer-defekt-chlor-phantasialand-100.html) ⭐️ 7.0/10

在微软 365 服务中断期间，德国一家酒店未能收到其泳池氯气投加系统发出的自动电子邮件警报，该系统发生故障并释放了过量氯气，导致 15 名客人氯气中毒。 这一事件凸显了将安全关键警报依赖于基于云的电子邮件的危险，强调了在可能造成人身伤害的系统中需要具有弹性和冗余的架构。 酒店的维护安全系统发送了一封关于氯气投加系统故障的电子邮件警报，但由于微软 365 服务中断，没有人收到该邮件，导致危险的氯气水平未被察觉，直到客人受到影响。

hackernews · DeepLogin · Nov 15, 18:36 · [社区讨论](https://news.ycombinator.com/item?id=50509411)

**背景**: 微软 365 是一套基于云的生产力套件，包括 Outlook 电子邮件，服务中断可能会中断通信。安全关键系统是指其故障可能导致伤害或死亡的系统，它们通常需要具有多层保护的稳健设计，而不仅仅是单一的电子邮件通知。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Microsoft_365_outage">Microsoft 365 outage</a></li>
<li><a href="https://en.wikipedia.org/wiki/Safety-critical_system">Safety-critical system - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者绝大多数指责酒店设计不佳，认为安全关键警报绝不应仅依赖电子邮件，并应有冗余检查。一些人指出，虽然微软的服务中断是一个因素，但责任在于酒店没有实施更具弹性的系统。

**标签**: `#cloud-reliability`, `#safety-critical-systems`, `#system-design`, `#incident-analysis`, `#email-dependency`

---

<a id="item-4"></a>
## [Sebastian Raschka 解释现代 LLM 中的位置嵌入](https://magazine.sebastianraschka.com/p/understanding-positional-embeddings) ⭐️ 7.0/10

Sebastian Raschka 发表了一篇技术深度文章，解释现代大型语言模型中的位置嵌入，涵盖隐式和显式方法，并预览了 2026 年开放权重模型中的选择。 位置嵌入对于 Transformer 理解 token 顺序至关重要，本文帮助从业者为他们的模型选择合适的方法，影响模型在长序列上的性能。 文章区分了来自因果注意力掩码的隐式位置信息和添加位置向量等显式方法，并指出“位置嵌入”是一个总称，涵盖学习到的绝对向量和固定的正弦编码。

hackernews · vismit2000 · Nov 15, 12:14 · [社区讨论](https://news.ycombinator.com/item?id=50506376)

**背景**: 大型语言模型并行处理 token，没有固有的顺序概念，因此必须注入位置信息。早期的 Transformer 使用固定的正弦编码或学习到的绝对嵌入，而现代模型越来越多地采用旋转位置嵌入（RoPE），它应用块对角旋转来编码相对位置，并且对超出训练长度的序列更具鲁棒性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://magazine.sebastianraschka.com/p/understanding-positional-embeddings">Understanding Positional Embeddings in Modern LLMs</a></li>
<li><a href="https://milvus.io/ai-quick-reference/what-are-position-embeddings-in-llms">What are position embeddings in LLMs?</a></li>
<li><a href="https://www.emergentmind.com/topics/rotary-positional-embeddings-rope">Rotary Positional Embeddings ( RoPE )</a></li>

</ul>
</details>

**社区讨论**: 评论者 programjames 认为文章侧重于实现而非理论，强调位置嵌入是群表示；例如，旋转位置嵌入是平移群的表示，这种群论视角为推导和参数化它们提供了原则性方法。

**标签**: `#LLM`, `#positional embeddings`, `#deep learning`, `#NLP`, `#group theory`

---

<a id="item-5"></a>
## [对 8900 笔众议员股票交易的分析发现中位数交易未能跑赢市场](https://arkanumdata.com/research/house-trades) ⭐️ 7.0/10

根据 Arkanum Data 发布的一份报告，一项对美国众议院议员 8900 笔股票交易的新分析发现，中位数交易并未跑赢市场。该研究引发了关于其方法论以及国会股票交易伦理的争论。 这些发现与当前关于是否应允许国会议员交易个股的政策辩论相关，因为它们表明普通议员可能并不具有系统性的信息优势。然而，该分析也引发了对潜在利益冲突和公众对政府机构信任的讨论。 该分析聚焦于中位数交易表现，批评者认为这可能掩盖了少数时机精准的交易所能产生的显著阿尔法收益。该研究似乎没有按交易规模加权，也没有考虑能够接触敏感信息的高级议员可能表现更优的可能性。

hackernews · Bluestein · Nov 15, 19:46 · [社区讨论](https://news.ycombinator.com/item?id=50510005)

**背景**: 2012 年的《STOCK Act》要求国会议员在 45 天内公开披露证券交易，旨在防止利用非公开信息进行内幕交易。内幕交易在涉及违反义务利用重大非公开信息交易时是非法的，但公司内部人士在适当报告的情况下进行合法内幕交易是允许的。衡量交易是否跑赢市场通常涉及计算阿尔法（相对于基准的超额收益），并使用加权平均值来考虑交易规模。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/STOCK_Act">STOCK Act - Wikipedia</a></li>
<li><a href="https://www.holdingsintel.com/guides/congressional-trading">Congressional Stock Trading: The STOCK Act Explained</a></li>
<li><a href="https://www.investopedia.com/ask/answers/102714/whats-difference-between-alpha-and-beta.asp">Mastering Alpha and Beta: Their Role in Portfolio Management</a></li>

</ul>
</details>

**社区讨论**: 评论者提出了方法论上的担忧，认为中位数表现是错误的指标，因为股票收益是偏态的，少数异常值驱动了大部分利润，而且普通议员并不是真正的内部人士。其他人认为，伦理辩论应聚焦于不当行为的外观和公众信任，而不是交易是否真正跑赢市场，同时一位评论者指出，大多数富有的议员在进入政界之前就已经富有。

**标签**: `#stock-trading`, `#congress`, `#insider-trading`, `#empirical-analysis`, `#ethics`

---

<a id="item-6"></a>
## [乌鸦决策速度超越人类，挑战“鸟脑”偏见](https://www.nytimes.com/2026/11/15/science/birdbrain-crows-birds-research-decision.html) ⭐️ 6.0/10

《纽约时报》一篇科学文章报道，乌鸦做出决策的速度大约是人类的两倍，颠覆了传统上“鸟脑”的贬义说法。该文章聚焦于鸦科动物的认知研究，并在 Hacker News 上引发了关于替代性大脑结构和智能趋同进化的讨论。 这一发现挑战了复杂认知必须依赖哺乳动物大脑结构的假设，表明智能可以通过不同的神经架构产生。它对神经科学、进化生物学以及我们对动物心智的理解都具有重要意义。 研究表明，尽管乌鸦缺乏分层的大脑皮层（哺乳动物大脑中被视为最高整合中心的结构），它们仍能实现更快的决策。评论者还指出，较小的大脑可能带来更短的神经连接和更快的反馈回路。

hackernews · gumby · Nov 15, 17:53 · [社区讨论](https://news.ycombinator.com/item?id=50509023)

**背景**: 趋同进化是指不同谱系的物种独立演化出相似特征，例如哺乳动物、鸦科动物和章鱼所展现的复杂智能。鸟类大脑在结构上与哺乳动物大脑不同——例如缺乏分层的新皮层——但近期研究表明，其大脑皮层（pallium）中的神经元具有与哺乳动物皮层细胞相似的分子特征和回路。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Convergent_evolution">Convergent evolution - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Avian_brain">Avian brain - Wikipedia</a></li>
<li><a href="https://www.uchicagomedicine.org/forefront/biological-sciences-articles/why-birds-are-smarter-than-you-think">Why birds are smarter than you think - UChicago Medicine</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者强调，智能至少独立演化了三次（哺乳动物、鸦科动物、章鱼），并讨论了鸟类不同的神经元设计和大脑架构如何提供了通往认知的替代路径。一些人批评标题的表述，指出“鸟脑”并不暗示决策缓慢；另一些人则认为较小的大脑允许更快的反馈回路，并指出鸟类的磁感应和精密生物钟进一步证明其智能被低估。

**标签**: `#neuroscience`, `#animal-cognition`, `#evolution`, `#science`, `#hackernews-discussion`

---

<a id="item-7"></a>
## [Turbo Pascal 的微小体积引发对现代软件膨胀的讨论](https://prog21.dadgum.com/116.html) ⭐️ 6.0/10

James Hague 在 2011 年的一篇博客文章中指出，Turbo Pascal 作为一个完整的编译器和 IDE，其体积比许多现代单个二进制文件（如 `touch` 命令）还要小。该文章在 Hacker News 上重新引发关注，产生了 84 条评论，讨论软件膨胀、效率以及 Anders Hejlsberg 的遗产。 讨论凸显了人们日益担忧现代软件为了开发者生产力而牺牲效率，导致二进制文件膨胀和资源需求增加。同时，它也强调了 Anders Hejlsberg 的持久影响力，他在 Turbo Pascal、Delphi、C# 和 TypeScript 上的工作塑造了主流开发。 Turbo Pascal 以其极快的编译速度和紧凑的体积而闻名，最初版本可以放在一张软盘上。这种比较可能不完全公平，因为现代二进制文件包含了更多功能、安全措施和依赖项，但它仍然说明了软件设计中的权衡。

hackernews · ksec · Nov 15, 13:44 · [社区讨论](https://news.ycombinator.com/item?id=50506894)

**背景**: Turbo Pascal 是 Anders Hejlsberg 在 20 世纪 80 年代于 Borland 开发的 Pascal 编译器和 IDE，以其在 CP/M 和 MS-DOS 上的速度和效率而闻名。软件膨胀是指软件随时间变得更大更慢的趋势，通常由于添加功能或抽象层。Anders Hejlsberg 后来设计了 Delphi、C# 和 TypeScript，成为编程语言设计的关键人物。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Turbo_Pascal">Turbo Pascal</a></li>
<li><a href="https://en.wikipedia.org/wiki/Anders_Hejlsberg">Anders Hejlsberg</a></li>
<li><a href="https://en.wikipedia.org/wiki/Software_bloat">Software bloat</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞 Anders Hejlsberg 是最伟大的语言设计师之一，列举了他在 Turbo Pascal、Delphi、C# 和 TypeScript 上的工作。一些人认为这种比较不公平，因为现代软件必须处理更多复杂性，而另一些人则感叹像 `touch` 这样简单命令的低效，并质疑为什么 Pascal 尽管有影响力却衰落了。

**标签**: `#software-efficiency`, `#programming-languages`, `#turbo-pascal`, `#software-bloat`, `#history-of-computing`

---

<a id="item-8"></a>
## [Emacs 作为浏览器：基于文本的网络实验](https://joshblais.com/blog/emacs-as-my-browser/) ⭐️ 6.0/10

一篇博客文章描述了作者使用 Emacs（特别是其内置的 eww 浏览器）作为主要网页浏览器的体验。该文章在 Hacker News 上引发了 80 条评论的讨论，内容涉及文本浏览的实际限制和替代工具。 这一实验凸显了极简的文本工具与现代商业网络之间的差距，后者严重依赖 JavaScript 和 CSS。它引起了重视简洁性、控制力和无干扰环境的开发者及 Emacs 爱好者的共鸣。 eww 是 GNU Emacs 内置的轻量级浏览器，能渲染基本 HTML，但不支持 JavaScript 和 CSS，导致许多现代网站无法使用。像 xwidget 嵌入 WebKit 或 w3m、Dillo 等文本浏览器提供了不同的权衡，但都无法完全复制主流浏览器的体验。

hackernews · nyc111 · Nov 15, 15:21 · [社区讨论](https://news.ycombinator.com/item?id=50507553)

**背景**: Emacs 是一个高度可扩展的文本编辑器，以其庞大的包生态系统而闻名，其中包括 eww，一个专注于可读性的网页浏览器。eww 由 Lars Ingebrigtsen 于 2013 年创建，使用 shr.el 解析和显示 HTML，但有意省略了 JavaScript 和 CSS，以保持简单和快速。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Eww_(web_browser)">eww (web browser) - Wikipedia</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_mono/eww.html">Emacs Web Wowser - GNU eww - web browser in Emacs - LinuxLinks EWW (GNU Emacs Manual) Web Browsing In Emacs | Irreal How do you browse the web in Emacs? Do you use a ... - Reddit EWW and my extras (text-based Emacs web browser) | Protesilaos</a></li>
<li><a href="https://www.linuxlinks.com/eww/">eww - web browser in Emacs - LinuxLinks</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，现代商业网站与 eww 配合不佳，而静态网站和博客则没问题。一些人分享了变通方法，如使用 w3m-mode 进行会话管理和显示图片，另一些人讨论了意识形态动机，例如 Richard Stallman 基于电子邮件的浏览方式。还有人表达了对 HTTP(S) 的内容寻址替代方案的渴望。

**标签**: `#Emacs`, `#web browsing`, `#eww`, `#text-based interfaces`, `#Hacker News`

---

<a id="item-9"></a>
## [法院驳回 DRAM 价格操纵案撤诉动议](https://litnews.ai/articles/garciaguirre-samsung-sk-hynix-micron-dram-conspiracy-suit-survives-dismissal) ⭐️ 6.0/10

一名联邦法官驳回了针对三星、SK 海力士和美光的一起集体诉讼的撤诉动议，该诉讼指控这三家公司合谋操纵 DRAM 价格，案件得以继续审理。诉讼称，这些公司以转向 HBM 生产为掩护，削减 DDR3 和 DDR4 产量，从而推高内存成本。 这一裁决意味着反垄断指控将进入证据开示阶段，可能曝光内部通信记录，并加大对三大 DRAM 供应商的法律压力。对消费者和企业而言，此案凸显了内存价格波动的持续担忧，这直接影响个人电脑、服务器和 AI 基础设施的硬件预算。 该诉讼最初由 Hagens Berman 于 2018 年提起，此前曾被驳回；此次新裁决允许案件继续推进。被告被指控利用行业转向用于 AI 芯片的高带宽内存（HBM）作为借口，减少较旧的 DDR3 和 DDR4 内存生产，导致内存价格创下历史新高。

hackernews · ybathaee · Nov 15, 01:18 · [社区讨论](https://news.ycombinator.com/item?id=50502988)

**背景**: DRAM（动态随机存取存储器）是计算机中用于短期数据存储的主要内存类型。三星、SK 海力士和美光共同控制着全球 DRAM 市场的绝大部分份额。过去，这些公司曾因涉嫌价格操纵面临法律诉讼，包括 2000 年代的一起重大案件，导致数十亿美元罚款。当前诉讼在 AI 需求推动的新一轮涨价潮中，再次引发类似担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DRAM_industry_price_fixing">DRAM industry price fixing - Wikipedia</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/samsung-sk-hynix-and-micron-sued-over-alleged-dram-price-fixing-amid-record-memory-costs">Samsung, SK hynix, and Micron sued over alleged DRAM price ...</a></li>
<li><a href="https://settlementinsight.com/dram-lawsuit">DRAM Lawsuit: Samsung, SK Hynix, Micron Case Survives ...</a></li>

</ul>
</details>

**社区讨论**: 评论者对高昂的内存价格表示不满，一位研究人员指出，256 GB 内存现在要价 4000-5000 美元，给研究预算带来压力。其他人则讨论市场动态，有人认为转向 DDR5 和 HBM 是合理的升级而非合谋，还有人批评提交 AI 生成的新闻内容。

**标签**: `#DRAM`, `#price-fixing`, `#hardware`, `#legal`, `#market`

---

<a id="item-10"></a>
## [阿波罗任务携带榴弹发射器用于地震实验](https://space.stackexchange.com/questions/37775) ⭐️ 6.0/10

Space Stack Exchange 上的一个问答解释称，部分阿波罗任务携带榴弹发射器是作为阿波罗月面实验包（ALSEP）中主动地震实验（ASE）的一部分，使用迫击炮发射爆炸物进行地震剖面测量。 这凸显了阿波罗计划中为进行月球科学而采用的巧妙工程解决方案，讨论还涉及苏联的生存枪支，提供了对太空任务设备的比较视角。 ASE 使用了一个带有 21 个小型爆炸起爆器的撞击装置和一个火箭榴弹发射器，能够向距离地震仪 150、300、900 和 1500 米处发射四枚榴弹，并从地球发送“arm grenades”和“fire grenades”等指令。

hackernews · Skyfall106 · Nov 15, 09:06 · [社区讨论](https://news.ycombinator.com/item?id=50505271)

**背景**: 阿波罗月面实验包（ALSEP）是阿波罗宇航员部署的一系列科学仪器，旨在月球上自主运行。主动地震实验（ASE）是阿波罗 14 号和 16 号上 ALSEP 的一部分，旨在使用爆炸物和地震仪研究月球地下结构。迫击炮包发射榴弹产生地震波，使科学家能够推断月球内部结构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Active_Seismic_Experiment">Active Seismic Experiment - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/TP-82">TP - 82 - Wikipedia</a></li>
<li><a href="https://www.ninfinger.org/karld/My+Space+Museum/ASE.htm">Experiment Operations During Apollo EVAs</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者指出，这个问题可能是一个用户每日发布系列的一部分，并讨论了苏联宇航员携带的 TP-82 生存枪，用于在西伯利亚防御野生动物。一些人还指出，问题的答案已在引用的 NASA 手册中提供。

**标签**: `#space`, `#apollo`, `#history`, `#engineering`, `#hacker-news`

---

<a id="item-11"></a>
## [开发者展示用 Odin 编写的 NES 模拟器](https://lucypero.com/lucynes.html) ⭐️ 6.0/10

一位开发者发布了一款用 Odin 编程语言实现的 NES 模拟器，展示了该语言在底层模拟项目中的可行性。 该项目凸显了 Odin 作为系统编程和模拟领域的有力替代方案，可能吸引更多开发者使用该语言并激发类似项目。 该模拟器完全用 Odin 从头编写，利用了该语言的手动内存管理和 C FFI，但可能面临任天堂激进的知识产权保护的法律审查。

hackernews · frostbyte7 · Nov 15, 12:51 · [社区讨论](https://news.ycombinator.com/item?id=50506588)

**背景**: Odin 是由 Bill Hall 于 2016 年创建的一种通用系统编程语言，专为高性能和面向数据编程而设计。NES 模拟涉及复制游戏机的 6502 CPU、PPU 和 APU，通常使用基于卡带的映射器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://odin-lang.org/">Odin Programming Language</a></li>
<li><a href="https://www.copetti.org/writings/consoles/nes/">NES / Famicom Architecture | A Practical Analysis</a></li>
<li><a href="https://grokipedia.com/page/Odin_programming_language">Odin (programming language) — Grokipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者赞扬了 Odin 的手动内存管理和 C FFI 等功能，讨论了 NES 硬件的奇特之处，并指出了“NES”在英式与美式发音上的差异。一些人提出了对任天堂法律立场和 Odin 对 LLVM 依赖的担忧。

**标签**: `#emulation`, `#odin`, `#nes`, `#programming-languages`, `#retro-computing`

---

<a id="item-12"></a>
## [datasette-llm 0.1a11 新增对 OpenAI 兼容端点的支持](https://simonwillison.net/2026/Nov/14/datasette-llm/) ⭐️ 6.0/10

datasette-llm 0.1a11 是 Datasette 的中间插件，用于为其他插件配置 LLM，现在支持 OpenAI 兼容端点。这使得 Datasette 可以使用由 LM Studio、Ollama、llama.cpp 或任何遵循 OpenAI 伪标准网络协议的服务托管的模型。 此更新让 Datasette 用户能够完全使用本地模型运行 datasette-agent 等 AI 驱动的插件，从而提升隐私性并避免 API 费用。它反映了本地 LLM 工具采用 OpenAI API 格式作为事实标准的增长趋势。 用户可以通过 plugins.datasette-llm.default_model 设置配置默认模型，指定 model、model_name 和 api_base（例如 LM Studio 的 http://localhost:1234/v1）。该版本是 alpha 版（0.1a11），聊天界面示例需要 datasette-agent 插件。

rss · Simon Willison · Nov 14, 23:59

**背景**: Datasette 是一个用于探索和发布数据的开源工具，具有扩展其功能的插件系统。datasette-llm 充当配置层，使其他插件可以共享 LLM 设置。OpenAI 兼容端点是一种常见接口，许多本地推理服务器现在都实现它，允许工具轻松在托管和本地模型之间切换。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.datasette.io/en/stable/plugins.html">Plugins - Datasette documentation</a></li>
<li><a href="https://lmstudio.ai/docs/developer/core/server">LM Studio as a Local LLM API Server</a></li>
<li><a href="https://restfulapi.net/openai-compatible-api/">What Is an OpenAI-Compatible API? Endpoints and Pitfalls</a></li>

</ul>
</details>

**标签**: `#datasette`, `#llm`, `#openai-api`, `#local-models`, `#plugins`

---