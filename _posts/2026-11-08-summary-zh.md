---
layout: default
title: "Horizon Summary: 2026-11-08 (ZH)"
date: 2026-11-08
lang: zh
---

> From 13 items, 10 important content pieces were selected

---

1. [高盛从银行家和交易员处撤下 Claude Code](#item-1) ⭐️ 8.0/10
2. [博主与 HN 讨论同时处理多个 AI 编码会话导致的“AI 脑疲劳”](#item-2) ⭐️ 7.0/10
3. [Outlook.com 静默拒收未配置 DMARC 域名的邮件](#item-3) ⭐️ 7.0/10
4. [Llama-modchip 在 64GB 内存上无 GPU 运行 284B DeepSeek 模型](#item-4) ⭐️ 7.0/10
5. [文章主张写作是核心思维工具，而非仅仅记录](#item-5) ⭐️ 7.0/10
6. [英伟达董事会调查 CEO 黄仁勋遭外国情报机构针对事件](#item-6) ⭐️ 7.0/10
7. [开发者从 Claude Code 转向 Pi 编码工具，引发热议](#item-7) ⭐️ 7.0/10
8. [微控制器上的即时位图文本渲染](#item-8) ⭐️ 7.0/10
9. [博客主张智能体记忆需要类似 OpenTelemetry 的开放格式](#item-9) ⭐️ 7.0/10
10. [文章重提彼得原理，引发 Hacker News 热议](#item-10) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [高盛从银行家和交易员处撤下 Claude Code](https://www.thestateofai.com/news/goldman-sachs-claude-code-traders-bankers) ⭐️ 8.0/10

据报道，高盛正在从其银行家和交易员的工作站上移除 Anthropic 的 Claude Code AI 编程代理，此事在 Hacker News 上引发了 410 分、253 条评论的热烈讨论。此举发生在 Anthropic 首次公开募股（IPO）前几周，而高盛据称正是该 IPO 的牵头承销商。 这是一个高价值的行业信号：一家大型金融机构撤下一款广泛使用的 AI 编程代理，引发了关于代理安全风险、基于消费的计费摩擦以及在受监管行业中企业 AI 采用挑战的疑问。这可能影响其他银行和企业对待代理式 AI 工具的方式。 社区成员指出，Claude Code 仅从交易员处移除，而交易员独有发送订单的权限，这暗示可能发生了操作损失而非主动决策。其他人强调，在可访问客户、交易和专有信息的工作站上运行半无人值守的代理会形成安全风险的“致命三要素”。

hackernews · TheWiggles · Nov 8, 18:16 · [社区讨论](https://news.ycombinator.com/item?id=50415628)

**背景**: Claude Code 是 Anthropic 的 AI 编程代理，能够自主编写、编辑和执行代码。企业环境中的 AI 代理会带来提示注入和级联故障等安全风险，尤其是在被授予访问敏感数据和内部网络权限时。AI 服务的基于令牌的计费模式可能导致不可预测的成本，促使一些企业寻求固定费率的替代方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.obsidiansecurity.com/blog/ai-agent-security-risks">Top AI Agent Security Risks and How to Mitigate Them</a></li>
<li><a href="https://salt.security/blog/top-security-risks-of-ai-agents">Top Security Risks of AI Agents in 2026 (And How to Mitigate ...</a></li>
<li><a href="https://www.revalorgrowth.com/post/rethinking-per-seat-pricing-in-the-age-of-ai-why-token-models-are-the-next-frontier">Rethinking Per-Seat Pricing in the Age of AI : Why Token Models Are...</a></li>

</ul>
</details>

**社区讨论**: 评论者提供了多种解释：一人认为此举纯粹是因为代理访问敏感数据、电子邮件、互联网和内部网络构成的“致命三要素”；另一人表示其组织因长期计费超支而收回 Claude 访问权限，而 Gemini 凭借固定计费正在胜出；还有人质疑时机，鉴于高盛在 Anthropic IPO 中的角色，并推测发生了涉及交易员下单权限的操作损失。

**标签**: `#AI agents`, `#enterprise AI adoption`, `#security`, `#Anthropic`, `#fintech`

---

<a id="item-2"></a>
## [博主与 HN 讨论同时处理多个 AI 编码会话导致的“AI 脑疲劳”](https://sergeykuhne.com/blog/fighting-ai-brain-fry) ⭐️ 7.0/10

sergeykuhne.com 上的一篇题为《How I Fight AI Brain Fry》的博客文章在 Hacker News 上引发了讨论（83 分，56 条评论），主题是开发者在管理多个并行 AI 编码会话时面临的认知过载。评论者分享了各自的策略，包括控制节奏、限制并发会话数量以及保留人类反思时间。 这场讨论凸显了 AI 辅助软件开发中日益增长的文化与生产力挑战：随着开发者采用多个 AI 代理，上下文切换和监督带来的精神负担可能抵消生产力提升。这表明行业可能需要重新思考工作流程和角色设计，以应对新的认知需求，而不仅仅是关注工具能力。 评论者描述了具体策略，例如将并发会话限制在 2-3 个、接受空闲时间作为生产力的一部分，以及使用移动设备保持灵活性。一位早期 AI 编码代理开发者强调 AI 不会感到疲劳，并敦促开发者“给自己作为人类的空间”，而不是匹配机器的节奏。

hackernews · kyunez · Nov 8, 19:37 · [社区讨论](https://news.ycombinator.com/item?id=50416363)

**背景**: “AI 脑疲劳”一词最近出现，用于描述因过度监督 AI 工具超出个人认知能力而导致的精神疲劳，2026 年《哈佛商业评论》等媒体对此进行了报道。它不同于普通的职业倦怠，可能表现为精神恍惚、决策变慢和头痛。随着 AI 编码代理能力增强并支持并行运行，开发者越来越面临管理多个会话的挑战，每个会话都有自己的上下文和状态。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hbr.org/2026/03/when-using-ai-leads-to-brain-fry">When Using AI Leads to “Brain Fry” - Harvard Business Review</a></li>
<li><a href="https://builtin.com/articles/ai-brain-fry-software-developers">AI Brain Fry: Why Developers Feel Overloaded by AI Agents ...</a></li>
<li><a href="https://agentspaces.co/blog/the-multitasking-mirage-why-developers-struggle-to-manage-multiple-ai-agents-effectively">The Multitasking Mirage: Why Developers Struggle to Manage Multiple ...</a></li>

</ul>
</details>

**社区讨论**: HN 讨论中既有赞同也有反对：一些评论者主张限制并发会话并休息，而另一些人质疑为何要启动并行线程，认为专注于单一任务能带来更高质量。一位早期 AI 编码代理开发者的观点引人注目，他敦促开发者不要试图匹配机器的节奏，而要休息和反思。

**标签**: `#ai-assisted-development`, `#developer-productivity`, `#cognitive-load`, `#hackernews-discussion`, `#software-engineering-culture`

---

<a id="item-3"></a>
## [Outlook.com 静默拒收未配置 DMARC 域名的邮件](https://mailroute.net/blog/outlook-rejecting-email-without-dmarc) ⭐️ 7.0/10

Outlook.com 已开始静默拒收未配置 DMARC 记录的域名所发送的邮件，且不向发件人提供明确的退信或通知。这一运营变更影响了许多尚未实施 DMARC 认证的发件人。 作为主要电子邮件提供商的这一举措迫使 DMARC 得到广泛采用，影响合法发件人的送达率，并引发了对电子邮件拦截做法透明度的担忧。这标志着行业趋向更严格的电子邮件认证要求。 该拒收似乎针对高流量发件人，有报告显示未认证邮件会收到 550 5.7.515 错误，而目前仅有约 22% 授权 Outlook.com 的域名执行了 DMARC。这种静默拦截方式使发件人难以诊断和解决问题。

hackernews · xmddmx · Nov 8, 19:20 · [社区讨论](https://news.ycombinator.com/item?id=50416158)

**背景**: DMARC（基于域的消息认证、报告和一致性）是一种电子邮件认证协议，建立在 SPF 和 DKIM 之上，用于防止域名欺骗。它允许域名所有者发布策略，指定接收方应如何处理未认证的电子邮件。像微软这样的主要提供商正日益强制执行 DMARC 以打击垃圾邮件和网络钓鱼。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DMARC">DMARC - Wikipedia</a></li>
<li><a href="https://defaults.exposed/en/fix/guides/outlook-rejecting-mail">Outlook Rejecting Your Email | Defaults.Exposed</a></li>
<li><a href="https://mailtester.com/blog/outlook-com-high-volume-sender-spf-dkim-dmarc-alignment-rules/">Outlook . com Alignment Rules | MailTester</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍支持拒收未配置 DMARC 的域名，但批评缺乏透明度，一些人指出 Outlook.com 还使用非公开且难以申诉的黑名单。其他人认为这一变化来得太晚，发件人早就应该采用 DMARC，而一些人则担心对遗留系统的影响。

**标签**: `#email`, `#DMARC`, `#deliverability`, `#Microsoft`, `#security`

---

<a id="item-4"></a>
## [Llama-modchip 在 64GB 内存上无 GPU 运行 284B DeepSeek 模型](https://github.com/synchopate/llama-modchip) ⭐️ 7.0/10

一个名为 llama-modchip 的 GitHub 项目声称能在仅有 64GB 内存且无 GPU 的系统上运行 284B 参数的 DeepSeek 模型，通过激进量化和 CPU 处理实现推理。该项目在 Hacker News 上引发了关于其实际功能与权衡的讨论。 该项目通过展示无需昂贵 GPU 即可在消费级硬件上运行超大模型，推动了本地 AI 的边界，可能降低数据主权 AI 部署的门槛。它也凸显了量化技术在使大模型普及方面日益增长的重要性。 该方法依赖 llama.cpp 进行 CPU 推理，并使用极端量化（可能每权重 1-2 位）将 284B 模型塞进 64GB 内存。然而，社区成员指出这种激进的量化会显著降低输出质量，且有人质疑该仓库相比原生 llama.cpp 是否有实质性改进。

hackernews · joshcsimmons · Nov 8, 10:22 · [社区讨论](https://news.ycombinator.com/item?id=50411961)

**背景**: DeepSeek 是一系列大语言模型，其 284B 版本是一个混合专家（MoE）模型，总参数达 2840 亿，但每个 token 仅激活 130 亿参数，从而降低了计算负载。量化是一种降低模型权重精度（例如从 16 位降至 4 位）以节省内存并加速推理的技术，但可能损害准确性。llama.cpp 是一个流行的开源库，用于在 CPU 上高效运行大语言模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/ggml-org/llama.cpp">GitHub - ggml-org/llama.cpp: LLM inference in C/C++</a></li>
<li><a href="https://canitrun.dev/models/deepseek-v4-flash/">DeepSeek V4 Flash 284 B VRAM Requirements: Runs on... | CanItRun</a></li>
<li><a href="https://arxiv.org/pdf/2411.02355">"Give Me BF16 or Give Me Death"? Accuracy-Performance Trade - Offs ...</a></li>

</ul>
</details>

**社区讨论**: 评论者既兴奋又怀疑：一些人分享了实用的成本/性能见解，指出低于 800 美元的系统就能达到可用速度，而另一些人警告低于 4 位的量化通常会导致显著的质量损失。一个关键担忧是该仓库是否真正提供了新颖功能，因为一位用户发现其在 CPU 上的表现与原生 llama.cpp 相似。

**标签**: `#local-llm`, `#quantization`, `#deepseek`, `#cpu-inference`, `#llama.cpp`

---

<a id="item-5"></a>
## [文章主张写作是核心思维工具，而非仅仅记录](http://muratbuffalo.blogspot.com/2026/11/writing-as-thinking-tool.html) ⭐️ 7.0/10

Murat Buffalo 的一篇博客文章主张，写作不仅仅是记录结果的方式，更是一种基本的认知思维工具，该文在 Hacker News 上引发了 226 分、72 条评论的讨论。 这一观点挑战了将写作视为最后一步的常见看法，并对科学、设计和软件工程领域的专业人士如何开展创造性和问题解决过程具有启示意义。 文章强调，清晰的思维和多次草稿对于有效传达想法至关重要，社区评论则将这一理念扩展到设计（Figma 原型制作）、编程和纸上草图等思维工具。

hackernews · jruohonen · Nov 8, 10:41 · [社区讨论](https://news.ycombinator.com/item?id=50412067)

**背景**: 写作作为思维工具是认知科学和教育学中的一个概念，认为写作行为有助于组织和澄清思维。这一理念常在学术写作、设计思维和软件开发等语境中讨论，因为将想法外化可以带来更深刻的见解。

**社区讨论**: 评论者大多赞同并扩展了这一观点：billypilgrim 分享了写作如何厘清他的博士研究，drewbeck 将其与设计原型制作相比较，lilerjee 和 hoppp 指出编程和草图也是思维工具。

**标签**: `#writing`, `#cognition`, `#productivity`, `#design`, `#software-engineering`

---

<a id="item-6"></a>
## [英伟达董事会调查 CEO 黄仁勋遭外国情报机构针对事件](https://nvidianews.nvidia.com/news/statement-from-nvidia-board-of-directors) ⭐️ 7.0/10

英伟达董事会宣布启动独立调查，以回应有关创始人兼 CEO 黄仁勋成为外国情报行动目标的报道，调查将由独立董事和外部法律顾问监督。黄仁勋已同意配合审查，此前有报道称他与一名被美国官员认定为中国情报人员的商业高管存在亲密关系。 这是一起涉及全球市值最高半导体公司领导人的高风险公司治理和国家安全事件，该公司正处于 AI 热潮和美中科技紧张关系的中心。调查结果可能影响英伟达的领导层稳定性、投资者信心，以及美国政府对该企业受外国影响程度的看法。 调查由独立董事组成的委员会在外部法律顾问协助下监督进行，黄仁勋已同意配合。董事会声明是针对近期报道发布的，彭博社报道称此次调查是在黄仁勋承认婚外情后启动的；该情报行动的具体性质以及所寻求的信息仍不清楚。

hackernews · vincentchau · Nov 8, 20:26 · [社区讨论](https://news.ycombinator.com/item?id=50416801)

**背景**: 黄仁勋于 1993 年联合创立英伟达，并自公司成立以来一直担任总裁兼 CEO，将公司从 PC 图形芯片厂商打造为 AI 热潮中 GPU 的主导供应商。英伟达的芯片处于美中科技竞争的核心，使其领导层成为外国情报机构的潜在目标。当相关指控可能给上市公司带来法律、声誉或国家安全风险时，启动独立董事会调查是标准的治理应对措施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nvidianews.nvidia.com/news/statement-from-nvidia-board-of-directors">Statement from NVIDIA Board of Directors</a></li>
<li><a href="https://www.nytimes.com/2026/11/08/technology/nvidia-investigation-jensen-huang-china.html">Nvidia Opens Investigation Into Jensen Huang’s Relationship ...</a></li>
<li><a href="https://videocardz.com/newz/nvidia-board-launches-investigation-into-alleged-chinese-spy-operation-targeting-jensen-huang">NVIDIA board launches investigation into alleged Chinese spy ...</a></li>

</ul>
</details>

**社区讨论**: 评论者强烈批评原标题具有误导性，澄清英伟达调查的是针对黄仁勋的情报行动，而非调查黄仁勋本人。一些人讨论了地缘政治动机，有人指出中国会针对重要人物，但提醒不应假定黄仁勋或英伟达有任何不当行为；还有人提到了此前关于一名疑似中国间谍与黄仁勋关系密切的报道。

**标签**: `#nvidia`, `#jensen-huang`, `#corporate-governance`, `#geopolitics`, `#security`

---

<a id="item-7"></a>
## [开发者从 Claude Code 转向 Pi 编码工具，引发热议](https://caleb.software/posts/claude-to-pi.html) ⭐️ 7.0/10

一位开发者发布博客文章，详细描述了从 Claude Code 切换到 Pi 作为其 LLM 编码工具（harness）的经历，在 Hacker News 上引发了 409 条评论的热烈讨论，涉及工具设计、服务条款风险和智能体架构。 这一对比凸显了 harness（围绕 LLM 的软件层）如何显著影响编码智能体的性能和用户体验，并提出了关于将第三方 harness 与 Anthropic 等专有模型结合使用的重要问题，因为这可能违反服务条款。 评论者指出，Pi 提供了更大的控制权和模型无关的灵活性，但将其与 Anthropic 订阅一起使用存在账户被封禁的风险，并且缺少 Claude Code 所依赖的未公开 API 功能，例如自定义请求头和隐藏标志。

hackernews · karagenit · Nov 8, 03:11 · [社区讨论](https://news.ycombinator.com/item?id=50410107)

**背景**: 智能体 harness（或称脚手架）是围绕大型语言模型的软件基础设施，使其能够作为 AI 智能体运行——处理工具调用、上下文管理以及与环境的交互。Claude Code 是 Anthropic 为其 Claude 模型开发的第一方 harness，而 Pi 是一个开源、模型无关的替代方案，让开发者对智能体的行为有更多控制权。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Agent_harness">Agent harness - Wikipedia</a></li>
<li><a href="https://docs.bswen.com/blog/2026-08-14-deepseek-harness-vs-pi/">DeepSeek Harness vs Pi : A Beginner's Comparison of... | BSWEN</a></li>
<li><a href="https://www.marktechpost.com/2026/09/18/best-open-source-agent-harnesses-for-local-llms-in-2026/">Best Open-Source Agent Harnesses for Local LLMs in 2026</a></li>

</ul>
</details>

**社区讨论**: 讨论总体上对 Pi 持积极态度，用户称赞其可定制性和控制力，但也有人警告违反服务条款的风险以及原生 harness 功能（如上下文压缩）的重要性。其他人则分享了他们不断演变的工作流程，随着 LLM 使用量的增长，从 TUI 转向 GUI 界面。

**标签**: `#LLM`, `#coding-assistants`, `#developer-tools`, `#AI-agents`, `#harness-design`

---

<a id="item-8"></a>
## [微控制器上的即时位图文本渲染](https://linebender.org/blog/jit-bitmap-text/) ⭐️ 7.0/10

Linebender 的一篇博客文章探讨了将字形即时（JIT）编译为机器码，以在微控制器上实现高效的位图文本渲染，从而无需存储字体位图。 这种方法可以显著降低资源受限嵌入式系统中文本渲染的内存占用并提升性能，从而在低端微控制器上实现更丰富的文本显示。 该技术动态生成每个字形的机器码，将像素数据作为立即数嵌入指令中，避免位图读取。然而，它可能以代码大小和复杂性为代价来节省内存。

hackernews · dmit · Nov 8, 10:42 · [社区讨论](https://news.ycombinator.com/item?id=50412072)

**背景**: 位图字体将每个字符存储为像素网格，在内存和闪存有限的微控制器上可能占用大量空间。JIT 编译通常用于 Java 或 JavaScript 等语言，在运行时编译代码以提高性能。将 JIT 应用于字体渲染是一种新颖的方法，模糊了数据与代码的界限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Font_Fusion">Font Fusion - Wikipedia</a></li>
<li><a href="https://stackoverflow.com/questions/95635/what-does-a-just-in-time-jit-compiler-do">compilation - What does a just - in - time ... - Stack Overflow</a></li>

</ul>
</details>

**社区讨论**: 评论者指出了相关先例，包括 1996 年的一项专利（US-6377261-B1），该专利将字形编译为指令，并分享了使用有损技术实现极端字体压缩（每个字符约 40 字节）的轶事。其他人讨论了只写屏幕等权衡以及低级图形编程的复古感。

**标签**: `#embedded systems`, `#text rendering`, `#JIT compilation`, `#microcontrollers`, `#font compression`

---

<a id="item-9"></a>
## [博客主张智能体记忆需要类似 OpenTelemetry 的开放格式](https://www.lorekit.io/blog/open-agent-memory-format) ⭐️ 7.0/10

lorekit.io 上的一篇博客文章提出，AI 智能体记忆应当拥有一个标准化的开放格式，类似于 OpenTelemetry 对遥测数据的标准化。该文章在 Hacker News 上引发了 158 分、102 条评论的讨论，争论这种标准化是否为时过早。 随着 AI 智能体的普及，记忆实现高度碎片化，导致跨框架共享、审计或迁移记忆变得困难。一个通用格式可以提升互操作性和工具生态，但过早标准化可能固化后来被证明错误的抽象。 评论者指出，智能体记忆在存储、表示乃至基本概念上仍在快速演进，并将过早标准化比作 SOAP 或 SGML。还有人认为 LLM 本身就能灵活解释非正式格式，从而降低了对严格标准的需求。

hackernews · mthines · Nov 8, 08:40 · [社区讨论](https://news.ycombinator.com/item?id=50411467)

**背景**: OpenTelemetry 是一个厂商中立的开源可观测性框架，提供统一的 API、SDK 和标准协议来采集追踪、指标和日志，由 OpenTracing 和 OpenCensus 合并而来。智能体记忆指 AI 系统存储和回忆过去交互以改进未来决策的能力。该博客文章认为，目前碎片化于众多临时实现的智能体记忆，需要一个类似的统一标准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://opentelemetry.io/docs/what-is-opentelemetry/">What is OpenTelemetry? OpenTelemetry — vendor-neutral observability framework · GitHub How OpenTelemetry Works: A Complete Guide - freeCodeCamp.org What Is OpenTelemetry? | IBM What is OpenTelemetry? A Comprehensive Guide - Better Stack Observability | Microsoft Learn</a></li>
<li><a href="https://www.ibm.com/think/topics/ai-agent-memory">What is AI agent memory? - IBM</a></li>
<li><a href="https://arxiv.org/abs/2512.13564">[2512.13564] Memory in the Age of AI Agents - arXiv.org The 6 Best AI Agent Memory Frameworks You Should Try in 2026 Memory for AI Agents | ai-agents-for-beginners Agent Memory — How AI Agents Remember (2026) | MyEngineeringPath Memory in the Age of AI Agents - arXiv.org</a></li>

</ul>
</details>

**社区讨论**: HN 讨论普遍持怀疑态度：许多人称其为过早优化，将其比作 SOAP 或 SGML，并质疑鉴于 Transformer 能解释非正式英语，这个问题是否真实存在。几位评论者还批评文章读起来像 LLM 生成的，少数人同意总体前提但认为时机未到。

**标签**: `#agent-memory`, `#opentelemetry`, `#ai-agents`, `#standards`, `#llm`

---

<a id="item-10"></a>
## [文章重提彼得原理，引发 Hacker News 热议](https://aworkinglibrary.com/writing/petered) ⭐️ 7.0/10

A Working Library 上的一篇题为《Petered》的文章重新探讨了彼得原理，在 Hacker News 上引发了 89 条评论的讨论，内容涉及为何优秀工程师常常成为糟糕的管理者，以及层级制度如何将不称职制度化。 讨论凸显了科技组织中一个长期存在的矛盾：基于技术能力的晋升往往导致管理岗位与能力不匹配，影响团队士气和公司绩效，并引起许多工程师的共鸣，他们曾目睹或亲身经历过这种现象。 评论者争论彼得原理是否忽略了层级制度本身才是根本原因，指出不称职的管理者往往依靠人际关系来生存，并质疑该原理假设人们无法在其岗位上改进的缺陷。

hackernews · adrianhoward · Nov 8, 10:56 · [社区讨论](https://news.ycombinator.com/item?id=50412152)

**背景**: 彼得原理由劳伦斯·J·彼得提出，观察到组织中的员工倾向于晋升到其不称职的级别，因为晋升基于过去的表现而非潜力。它常被用于讨论工程管理问题，即优秀的个人贡献者被提升到管理岗位，却缺乏足够的培训或领导才能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Peter_principle">Peter principle - Wikipedia</a></li>
<li><a href="https://learnmentalmodels.co/manager-problems/engineers-as-managers-struggle-and-fail">Engineers as Managers: Why They Often Struggle & Fail</a></li>
<li><a href="https://philocrux.com/answers/what-is-the-peter-principle/">What is the Peter Principle? The Science of Incompetence Explained</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了同事被提升到管理岗位后遭遇灾难性后果的警示故事，认为层级制度本身才是问题所在，因为管理被视为“高于”工程，并指出不称职的管理者通过人际关系生存，从而延续了“一流人才雇一流人才，二流人才雇三流人才”的动态。

**标签**: `#management`, `#career`, `#organizational-behavior`, `#peter-principle`, `#hackernews-discussion`

---