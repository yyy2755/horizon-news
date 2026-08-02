---
layout: default
title: "Horizon Summary: 2026-08-02 (ZH)"
date: 2026-08-02
lang: zh
---

> From 19 items, 16 important content pieces were selected

---

1. [Go 1.27 交互式导览重点介绍泛型和运行时修复](#item-1) ⭐️ 8.0/10
2. [Diátaxis 框架获得社区采用并推出多语言翻译](#item-2) ⭐️ 8.0/10
3. [关于 AI 发展的公开信：产业界与安全之争](#item-3) ⭐️ 8.0/10
4. [OpenAI 的 Astra 以每个 2000 美元解决 10 个十年未解数学难题](#item-4) ⭐️ 8.0/10
5. [英语学习者核心词汇的变迁（1953–2023）](#item-5) ⭐️ 7.0/10
6. [F*：一种通用的面向证明的编程语言](#item-6) ⭐️ 7.0/10
7. [Meshdiff：客户端 STL 比较工具](#item-7) ⭐️ 7.0/10
8. [Bor：面向 Linux 桌面的开源实时策略管理](#item-8) ⭐️ 7.0/10
9. [15 岁少年自制摆线齿轮箱，获社区赞誉](#item-9) ⭐️ 7.0/10
10. [勒古恩 2005 年文章重新定义技术：超越电子设备](#item-10) ⭐️ 7.0/10
11. [Karpathy 点赞 sqliteai/waste：一款新的 MoE 推理引擎](#item-11) ⭐️ 6.0/10
12. [RISC OS Open 庆祝成立 20 周年，专注 ARM 操作系统开发](#item-12) ⭐️ 6.0/10
13. [Karpathy 的 LLM 生成 3D 动画引发基准测试讨论](#item-13) ⭐️ 6.0/10
14. [中世纪《诺托里亚术》作为 AI 即时知识承诺的历史镜像](#item-14) ⭐️ 6.0/10
15. [MkLinux 在 Apple Workgroup Server 9150 上的怀旧故事](#item-15) ⭐️ 6.0/10
16. [Greg Brockman：人们不喜欢同事的 ChatGPT 在 Slack 上联系自己](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Go 1.27 交互式导览重点介绍泛型和运行时修复](https://victoriametrics.com/blog/go-1-27/index.html) ⭐️ 8.0/10

Go 1.27 的交互式导览已发布，展示了泛型方法、JSON v2、原生 UUID 支持以及运行时修复等关键特性。该导览旨在通过动手示例帮助开发者理解这些变化。 Go 1.27 是一个重要版本，引入了泛型方法等期待已久的功能，将简化代码并提高开发效率。运行时修复（包括与 Android MTE 的兼容性）增强了移动和系统级应用的安全性和可靠性。 该导览重点介绍了泛型方法，允许方法声明自己的类型参数，而此前这一功能仅限于函数。它还涵盖了新的 json/v2 包、原生 UUID 支持、goroutine 泄漏分析器，以及修复 runtime.findnull() 以兼容 Android MTE 的改动。

hackernews · Hixon10 · Aug 2, 01:35 · [社区讨论](https://news.ycombinator.com/item?id=49140218)

**背景**: Go 是一种静态类型、编译型编程语言，设计注重简洁和高效。泛型在 Go 1.18 中引入，但直到现在方法才能拥有自己的类型参数。Go 1.27 版本还包括标准库和运行时的更改，反映了该语言的持续演进。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://go.dev/doc/go1.27">Go 1.27 Release Notes - The Go Programming Language</a></li>
<li><a href="https://ademawan.medium.com/go-1-27-is-coming-what-many-developers-have-been-waiting-for-afcdfa00a8a4">Go 1.27 Is Coming: What Many Developers Have Been Waiting For</a></li>
<li><a href="https://medium.com/@arthurpro/go-1-27-is-coming-generic-methods-json-v2-and-more-749d08192f5a">Go 1.27 Is Coming: Generic Methods, json/v2, and more</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一：一些开发者觉得新的泛型方法语法令人困惑，而另一些人则赞赏运行时修复，如 MTE 兼容性。还有人担心自动排空 HTTP 响应体的静默行为变化，这可能会影响现有应用程序。

**标签**: `#Go`, `#programming language`, `#release`, `#generics`, `#runtime`

---

<a id="item-2"></a>
## [Diátaxis 框架获得社区采用并推出多语言翻译](https://diataxis.fr/) ⭐️ 8.0/10

Diátaxis，一个将技术文档分为四种类型的框架，在 Hacker News 上获得了大量社区关注（484 分，56 条评论）。作者 Daniele Procida 宣布正在进行多语言翻译，进行中的版本可在 diataxis-translated.readthedocs.io 查看。 该框架提供了一种系统化的文档方法，许多团队认为它很有价值，能提高清晰度和一致性。其日益增长的采用和翻译工作表明，软件工程领域对更好的文档实践有着广泛需求。 该框架将文档分为教程、操作指南、参考和解释四类，每类满足不同的用户需求。作者的翻译项目旨在让非英语使用者也能使用该框架，目前已有部分翻译完成。

hackernews · ryanseys · Aug 1, 20:33 · [社区讨论](https://news.ycombinator.com/item?id=49138188)

**背景**: Diátaxis 是一种务实且系统化的文档创建方法，在科技行业被广泛采用。它帮助写作者根据用户需求组织内容，避免常见问题，如将教程与参考资料混在一起。该框架常被与 DITA 和信息映射等其他文档方法论进行比较。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://diataxis.fr/">Diátaxis</a></li>
<li><a href="https://idratherbewriting.com/blog/what-is-diataxis-documentation-framework">What is Diátaxis and should you be using it with your ...</a></li>
<li><a href="https://github.com/evildmp/diataxis-documentation-framework">GitHub - evildmp/diataxis-documentation-framework: A systematic approach to creating better documentation. · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了积极的经验，一位成员表示在记录复杂代码库时它“非常棒”，但需要花精力规划页面标题。另一位提醒不要将其视为“金科玉律”，但认为它很有帮助，并建议在开始前通读网站。还有人指出这之前已被多次发布。

**标签**: `#documentation`, `#technical-writing`, `#software-engineering`, `#framework`

---

<a id="item-3"></a>
## [关于 AI 发展的公开信：产业界与安全之争](https://simonwillison.net/2026/Aug/2/open-letters/#atom-everything) ⭐️ 8.0/10

Simon Willison 总结了近期关于 AI 发展的公开信，特别是微软发起的《开放权重与美国 AI 领导力》公开信，该信由包括 NVIDIA、亚马逊和 OpenAI 在内的 235 家公司签署，以及 Anthropic 的回应。此外，《Pacing the Frontier》公开信发布，获得了 1324 名前沿 AI 公司员工的签名。 这些公开信凸显了 AI 安全和开源模型问题上的重大行业分歧，并可能影响美国的政策制定。其结果将塑造 AI 发展的未来，平衡创新与安全，并影响全球竞争力。 微软的公开信认为开放权重模型比封闭模型更安全，指出封闭模型存在单点故障，并支持将蒸馏视为合法技术。Anthropic 明显未签署该信，警告网络攻击等风险，并呼吁打击工业规模的蒸馏操作，但并未主张禁令。《Pacing the Frontier》则请求国际社会共同努力，以审慎推进自动化 AI 发展。

rss · Simon Willison · Aug 2, 04:16

**背景**: 开放权重模型是指公开其权重的 AI 模型，允许任何人使用、修改和研究。争论的焦点在于这种开放性是否带来安全风险，例如被恶意行为者滥用，还是能促进创新和透明度。美国政府曾出于安全考虑考虑限制开放权重模型，这引发了业界的回应。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.microsoft.com/en-us/corporate-responsibility/wp-content/uploads/2026/07/open-weight-models-letter_July26.pdf">Open Weights and American AI Leadership</a></li>
<li><a href="https://www.cnbc.com/2026/07/24/nvidia-microsoft-meta-open-weight-ai-models.html">Nvidia, Microsoft, Meta warn against 'premature restrictions' of open-weight models</a></li>
<li><a href="https://www.semafor.com/article/07/28/2026/chinese-open-weight-models-reignite-ai-safety-debate">Chinese open-weight models reignite AI safety debate | Semafor</a></li>

</ul>
</details>

**社区讨论**: 讨论反映了分歧：一些人支持公开信的观点，认为开放权重能增强安全性和创新，而另一些人则赞同 Anthropic 对潜在滥用的担忧。此外，关于大公司对政策的影响以及安全与进步之间的平衡也存在争论。

**标签**: `#AI policy`, `#open source`, `#AI safety`, `#industry influence`

---

<a id="item-4"></a>
## [OpenAI 的 Astra 以每个 2000 美元解决 10 个十年未解数学难题](https://simonwillison.net/2026/Aug/1/ten-advances-in-mathematics/#atom-everything) ⭐️ 8.0/10

2026 年 8 月 1 日，OpenAI 宣布其下一代主要模型的内部版本 Astra 解决了十个至少十年未有进展的长期数学问题。该公司声称每个解决方案在 GPT-5.6 Sol 代币价格下花费不到 2000 美元，并发布了 Lean 4 形式化证明和描述结果的论文。 这标志着 AI 辅助数学的一个重要里程碑，表明前沿模型能够以极低的成本解决长期未解的问题。它可能加速数学和理论计算机科学的研究，将数学家的角色转向创造性问题构建，而 AI 处理技术细节，正如陶哲轩所构想的“大数学”那样。 结果在 GitHub 仓库 openai/ten-proofs 中使用 Lean 4 进行了形式化，OpenAI 还发布了一篇论文和一份由 LLM 生成的 PDF，重建了推理轨迹。然而，帖子指出 OpenAI 没有披露他们尝试了多少问题但未成功，也没有公布使用的提示词。

rss · Simon Willison · Aug 1, 20:34

**背景**: Lean 4 是一个交互式定理证明器，允许计算机验证数学证明，确保正确性。GPT-5.6 是 OpenAI 最新的模型系列，有三个层级——Sol、Terra 和 Luna——按每百万 token 定价，其中 Sol 最贵，输入 5 美元，输出 30 美元。这一公告紧随 Anthropic 的 Claude Mythos Preview 发现密码学弱点之后，凸显了 AI 模型在研究领域做出重大贡献的趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://byteiota.com/openai-astra-multi-agent-model/">OpenAI Astra: Multi-Agent Model Solves 10 Decade-Old Math ...</a></li>
<li><a href="https://techwafer.com/openai-astra-solved-10-open-math-problems-for-2000/">OpenAI Astra: 10 Math Problems Solved for $2,000, Explained</a></li>
<li><a href="https://www.eesel.ai/blog/gpt-5-6-pricing">GPT-5.6 pricing (2026): Sol, Terra, and Luna costs explained</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论可能既有惊叹也有怀疑，一些人赞扬发布形式化证明的透明度，而另一些人则质疑未披露的失败和提示词的不透明。帖子本身提到数学家们“集体爆发了深蓝”，引用了 Kirwin Hampshire 文章中描述的精神危机。

**标签**: `#AI`, `#mathematics`, `#OpenAI`, `#research`, `#theoretical computer science`

---

<a id="item-5"></a>
## [英语学习者核心词汇的变迁（1953–2023）](https://pudding.cool/2026/07/essential-words/) ⭐️ 7.0/10

The Pudding 发布了一项数据驱动分析，展示了 1953 年至 2023 年间英语学习者核心词汇的变化，揭示了词汇表的显著变迁。1953 年的词汇中近四分之一已消失，而 2023 年的词汇中有 39%是新词。 该分析凸显了语言教学如何反映更广泛的文化和社会变迁，为教育者和语言学家提供了见解。它强调了语言的动态性，以及更新课程以满足当代交流需求的必要性。 文章将词汇分为“社交-交际”等层级，指出其规模虽几乎未变，但构成发生了巨大变化。“谦逊”、“忠诚”、“友谊”等词被“社区”、“身份”、“性别”等词取代，表明从人际美德转向更广泛的社会建构。

hackernews · c-oreills · Aug 2, 15:41 · [社区讨论](https://news.ycombinator.com/item?id=49145590)

**背景**: 英语教学通常依赖精选词汇表来优先教授词汇。这些列表基于频率和实用性，但也隐含地反映了当时的文化价值观和优先事项。The Pudding 的分析利用历史教科书和频率数据，追踪了七十年间的这些变化。

**社区讨论**: 评论者讨论了创建此类列表的难度，指出词汇优先级因目的而异（如旅行、电视、报纸）。一些人将这种变化归因于不平等加剧和“部落化”，另一些人则讨论了网页的滚动行为，显示出对分析及其呈现方式的不同观点。

**标签**: `#linguistics`, `#education`, `#data-analysis`, `#culture`, `#language-learning`

---

<a id="item-6"></a>
## [F*：一种通用的面向证明的编程语言](https://fstar-lang.org/) ⭐️ 7.0/10

F* 是一种成熟的、通用的面向证明的编程语言，通过依赖类型、SMT 求解和基于策略的定理证明来支持形式化验证。它支持将现有 C 代码库增量迁移到形式化验证的环境中。 F* 弥合了实用编程与形式化验证之间的鸿沟，允许开发者在保持性能以及与 C 语言互操作性的同时，证明其代码的属性。这对于航空航天、密码学和区块链等安全关键行业至关重要，因为这些领域对正确性的要求极高。 F* 结合了纯函数式编程和带效果编程，利用依赖类型和基于 SMT 的自动化。它已被用于现实项目，如 Everest 项目中的已验证 HTTPS，其 GitHub 仓库显示活跃的开发状态。

hackernews · ducktective · Aug 2, 12:31 · [社区讨论](https://news.ycombinator.com/item?id=49143925)

**背景**: 形式化验证是通过数学方法证明系统满足其规范的过程。F* 受 ML、Caml 和 OCaml 启发，旨在支持函数式和带效果编程，同时支持证明。它利用 SMT 求解器和交互式定理证明来自动化部分验证过程，使开发者更容易上手。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/F*_(programming_language)">F* (programming language) - Wikipedia</a></li>
<li><a href="https://fstar-lang.org/">F*: A Proof-Oriented Programming Language</a></li>
<li><a href="https://github.com/FStarLang/FStar">GitHub - FStarLang/FStar: A Proof-oriented Programming Language · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区评论情绪复杂：一些用户批评主页缺少语法示例，而另一些用户则称赞其增量迁移 C 代码的能力。还有关于其是否适合编译器验证以及与其他证明助手（如 Lean）的比较的问题。

**标签**: `#formal verification`, `#programming language`, `#proof-oriented`, `#F*`, `#functional programming`

---

<a id="item-7"></a>
## [Meshdiff：客户端 STL 比较工具](https://meshdiff.com/) ⭐️ 7.0/10

Meshdiff 是一款新的基于浏览器的工具，允许用户完全在客户端比较两个版本的 STL 文件，无需将数据上传到服务器。它提供三个视口来检查差异，社区建议添加同步旋转和 CI 集成等功能。 该工具解决了 3D 打印和 CAD 工作流程中的实际需求，在这些领域中跟踪 3D 模型的更改通常很麻烦。通过客户端运行，它提高了隐私性和速度，并且其集成到 CI 流水线的潜力可以自动化 3D 文件的视觉回归测试。 Meshdiff 使用客户端渲染，可能利用 WebGL 或 Three.js 来显示 STL 网格。该工具目前提供三个视口进行并排比较，社区提出了同步变换和用于 CI 集成的 CLI 等功能。

hackernews · projscope · Aug 2, 11:34 · [社区讨论](https://news.ycombinator.com/item?id=49143479)

**背景**: STL 是一种常用于 3D 打印和 CAD 的文件格式，将表面几何表示为三角网格。客户端渲染使用 JavaScript 在浏览器中处理网页内容，通过避免服务器上传可以提高隐私性和性能。像 Meshdiff 这样的工具是 WebAssembly 和 Three.js 驱动的浏览器内应用增长趋势的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/STL_(file_format)">STL (file format)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Client-side_rendering">Client-side rendering</a></li>

</ul>
</details>

**社区讨论**: 社区反应积极，用户称赞该工具的实用性和客户端方法。建议包括添加同步视口旋转、锁定视图以及将 Meshdiff 集成到 CI 流水线或作为 GitHub PR 触发器用于 3D 文件。一些用户还推荐了 BIM 和建筑领域的相关项目。

**标签**: `#3D`, `#STL`, `#visualization`, `#client-side`, `#developer tools`

---

<a id="item-8"></a>
## [Bor：面向 Linux 桌面的开源实时策略管理](https://getbor.dev/blog/2026-08-02-bor-v080-release/) ⭐️ 7.0/10

Bor，一个面向 Linux 桌面的开源集中式策略管理系统，发布了 0.8 版本，新增了对 Thunderbird、Microsoft Edge for Business 和 FirewallD 区域的支持。它使用 Go 代理和服务器，通过 mTLS/gRPC 实时流式传输策略，无需轮询。 这填补了 Linux 桌面管理领域的重大空白，为传统工具提供了一种现代的实时替代方案。它可能使管理大量 Linux 工作站的组织受益，尤其是那些寻求开源解决方案以避免 Windows Intune 等专有系统的组织。 Bor 的架构使用客户端上的轻量级 Go 代理和中央服务器，通过 mTLS/gRPC 实时流式传输策略。0.8 版本引入了新的策略类型，系统目前支持 Firefox、Chrome、KDE、dconf、polkit 和包管理，未来计划支持更多。

hackernews · eniac111 · Aug 2, 09:06 · [社区讨论](https://news.ycombinator.com/item?id=49142569)

**背景**: Linux 桌面管理通常依赖手动配置或 Ansible 等工具，这些工具使用定期轮询或基于推送的部署。dconf 是 GNOME 用于设置的配置数据库，而 polkit 控制系统级权限。mTLS（双向 TLS）确保客户端和服务器相互认证，gRPC 是一个支持流式传输的高性能 RPC 框架。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://help.gnome.org/system-admin-guide/dconf.html">Manage user and system settings with dconf - GNOME</a></li>
<li><a href="https://en.wikipedia.org/wiki/Polkit">Polkit - Wikipedia</a></li>
<li><a href="https://github.com/islishude/grpc-mtls-example">GitHub - islishude/ grpc - mtls -example: grpc mTLS example · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区反馈积极，用户对非营利组织的笔记本电脑管理表示兴趣，并询问自定义脚本执行和用户映射。问题还将 Bor 与 System76 的 Cosmic Sync 等工具进行比较，并询问 mTLS 与 SSH 的选择、无轮询策略执行以及竞争解决方案。

**标签**: `#Linux`, `#desktop management`, `#policy management`, `#open-source`, `#Go`

---

<a id="item-9"></a>
## [15 岁少年自制摆线齿轮箱，获社区赞誉](https://github.com/tom-ilan/cycloidal_gearbox) ⭐️ 7.0/10

一位名叫 Tom Ilan 的 15 岁开发者在 Hacker News 上分享了他自制的摆线齿轮箱项目，并附有详细的文档和制造参考。该项目托管在 GitHub 上，迅速获得了 285 分和 94 条评论的关注。 该项目凸显了年轻创客在硬件工程领域的潜力，表明年龄不是创造复杂机械装置的障碍。同时，它也展示了开源文档和社区支持在促进 STEM 教育和实践技能方面的价值。 该齿轮箱是一种摆线驱动装置，利用偏心凸轮和摆线盘实现高减速比、低背隙和紧凑尺寸。项目引用了既定标准，表明其注重质量和可制造性。

hackernews · tomilan · Aug 2, 02:07 · [社区讨论](https://news.ycombinator.com/item?id=49140396)

**背景**: 摆线齿轮箱，也称为摆线驱动装置，是一种利用摆线盘运动实现高减速比的减速器。它通过偏心凸轮驱动摆线盘旋转，与环形齿轮上的滚针啮合，从而实现平稳高效的动力传输。这类齿轮箱因其紧凑、坚固和低背隙而备受青睐，适用于机器人技术和工业机械等精密应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cycloidal_drive">Cycloidal drive - Wikipedia</a></li>
<li><a href="https://howtomechatronics.com/how-it-works/what-is-cycloidal-driver-designing-3d-printing-and-testing/">What is Cycloidal Driver? Designing, 3D Printing and Testing</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S1110016824001182">Design principle and numerical analysis for cycloidal drive considering clearance, deformation, and friction - ScienceDirect</a></li>

</ul>
</details>

**社区讨论**: 社区反应极为积极，许多评论者称赞这位年轻创客的工艺和文档。多位用户鼓励他去掉“想成为”的标签，认为他已经是一名工程师。还有人讨论了此类项目可能带来付费机会，从而绕开传统教育路径。

**标签**: `#mechanical engineering`, `#hardware`, `#DIY`, `#gearbox`, `#young maker`

---

<a id="item-10"></a>
## [勒古恩 2005 年文章重新定义技术：超越电子设备](https://www.ursulakleguin.com/a-rant-about-technology) ⭐️ 7.0/10

厄休拉·勒古恩 2005 年的文章《关于技术的吐槽》批评了现代对“技术”一词的狭隘使用，认为它应涵盖所有人类技能和知识，而不仅仅是电子设备。这篇文章在 Hacker News 上重新出现，引发了实质性的讨论。 这篇文章挑战了科技界的自我认知，敦促人们更广泛地理解技术，包括传统工艺和知识。它与关于技术定义和社会价值的持续辩论产生共鸣，影响我们看待创新和进步的方式。 勒古恩将技术定义为“人类与物质世界的主动交互”，并对比了常见的误用——将其局限于近期的复杂技术。文章强调，从石器到计算机，所有技术都是可学习的技能，并批评了现代技术相关的剥削。

hackernews · jamesgill · Aug 2, 14:51 · [社区讨论](https://news.ycombinator.com/item?id=49145201)

**背景**: 厄休拉·勒古恩是著名的科幻和奇幻作家，以《地海传说》系列和《黑暗的左手》等作品闻名。她的文章反映了一种哲学视角，早于当前关于技术角色的讨论，借鉴了她的人类学和文学背景。

**社区讨论**: 评论者称赞勒古恩精准的语言和谦逊的情感，有人指出它提炼了人们对技术追求的吸引力。其他人将其与史蒂夫·乔布斯关于人类相互依存的最后一封电子邮件相提并论，并讨论了科幻与奇幻之间的模糊界限，反思技术在小说的感知方式。

**标签**: `#philosophy`, `#technology`, `#essay`, `#Ursula K. Le Guin`, `#science fiction`

---

<a id="item-11"></a>
## [Karpathy 点赞 sqliteai/waste：一款新的 MoE 推理引擎](https://github.com/sqliteai/waste) ⭐️ 6.0/10

Andrej Karpathy 在 GitHub 上为 sqliteai/waste 仓库点了星标，该仓库是一个用 C 编写的可嵌入式推理引擎，能够通过从磁盘流式加载激活的权重，在内存受限的系统上运行完整的 2.78 万亿参数 Kimi K3 模型。 这位 AI 领域知名人物的点赞凸显了在消费级硬件上本地运行大型模型的日益增长的兴趣，这可能使前沿规模的 AI 模型无需庞大的服务器基础设施即可普及使用。 WASTE 没有第三方运行时依赖，将模型主干保留在内存中，直接从磁盘流式加载选定的专家，并将剩余内存用作有界的专家缓存。Kimi K3 模型发布时大小为 1.42 TB，转换后为 982 GB。

github · karpathy · Aug 2, 17:19

**背景**: 混合专家（MoE）模型每个 token 只激活其参数的一部分，从而在保持推理效率的同时拥有庞大的总参数量。WASTE 利用这一特性，将完整模型存储在磁盘上，仅将必要的专家加载到内存中，从而在内存有限的系统上实现推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/sqliteai/waste">GitHub - sqliteai / waste : Run the full 2.78-trillion-parameter Kimi...</a></li>
<li><a href="https://github.com/sqliteai/waste/blob/main/README.md">waste/README.md at main · sqliteai/waste · GitHub</a></li>
<li><a href="https://karpathy.ai/">Andrej Karpathy</a></li>

</ul>
</details>

**标签**: `#github`, `#karpathy`, `#sqlite`, `#ai`, `#unknown`

---

<a id="item-12"></a>
## [RISC OS Open 庆祝成立 20 周年，专注 ARM 操作系统开发](https://www.riscosopen.org/news/articles/2026/06/20/twenty-years-of-risc-os-open) ⭐️ 6.0/10

RISC OS Open（ROOL）于 2026 年 6 月 20 日庆祝其成立 20 周年，标志着这个由社区驱动的操作系统项目在维护和发展 RISC OS 方面已走过二十年。这一里程碑凸显了该项目在维护和演进由 Acorn Computers 最初创建的基于 ARM 的操作系统方面的坚持。 这一周年纪念凸显了 RISC OS 在复古计算和开源社区中的持久相关性，证明了一个小众平台在其原始创建者停止运营后仍能生存并适应。它也强调了人们对基于 ARM 的系统的持续兴趣，以及社区主导的软件保存的价值。 RISC OS Open Limited（ROOL）负责管理 RISC OS 的源代码，该代码于 2018 年 10 月在 RISC OS Developments 从 Castle Technology 收购知识产权后，以 Apache 2.0 许可证完全开源。该项目还在 2011 年引入了赏金计划以鼓励进一步开发，并继续支持基于 ARM 的硬件，如 Raspberry Pi。

hackernews · AlexeyBrin · Aug 2, 12:36 · [社区讨论](https://news.ycombinator.com/item?id=49143967)

**背景**: RISC OS 是一款模块化操作系统，由 Acorn Computers 在英国剑桥设计，于 1987 年首次发布，用于基于 ARM 的处理器。它以其支持的 RISC（精简指令集计算机）架构命名，并具有图形用户界面和窗口系统。尽管 Acorn 已不复存在，RISC OS 仍由 RISC OS Open 社区维持，该社区继续开发系统的 5.0 版本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/RISC_OS">RISC OS - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/RISC_OS_Open">RISC OS Open - Wikipedia</a></li>
<li><a href="https://www.riscosopen.org/content/">RISC OS Open: Welcome RISC OS Open - Wikipedia Complete OS Guide: RISC OS Open How It Works, Orientation and ... RISC OS Open: About RISC OS in Library RISC OS Open - grokipedia.com RISC OS Has Been Released to Open Source – Open-Electronics</a></li>

</ul>
</details>

**社区讨论**: 社区评论反映了怀旧和技术欣赏的混合情绪。一位用户分享了为 RISC OS 开发软件的个人经历，称这是他们学习开源开发的地方，而另一位用户则强调，鉴于许多用户在 2000 年之前就离开了，该项目的持久性令人惊讶。其他人则称赞 RISC OS 在 Raspberry Pi 上的快速启动时间，并指出了在该平台上编程的资源。

**标签**: `#RISC OS`, `#retro computing`, `#open source`, `#ARM`

---

<a id="item-13"></a>
## [Karpathy 的 LLM 生成 3D 动画引发基准测试讨论](https://twitter.com/karpathy/status/2083749667410727319) ⭐️ 6.0/10

Andrej Karpathy 分享了一条推文，展示了一个由 LLM 生成的 3D 动画，引发了关于将此类输出作为物理世界理解基准的讨论。该动画可能通过代码生成，展示了模型解释和渲染场景的能力。 这标志着从静态图像生成转向动态 3D 场景，作为评估 AI 物理世界理解的新前沿。它可能影响研究人员设计基准和评估模型能力的方式，超越文本和图像。 该动画由 LLM 生成，可能通过 three.js 代码实现，社区成员指出其质量粗糙且对文本理解有误（例如比尔博的消失）。一些人认为此类输出可作为物理理解的定性基准，而另一些人则警告不要过度解读模型的代码生成能力。

hackernews · delichon · Aug 2, 04:05 · [社区讨论](https://news.ycombinator.com/item?id=49140998)

**背景**: 大型语言模型（LLM）最近从生成文本和图像发展到生成 3D 动画代码，通常使用 three.js 等库。像 PhysBench 和 PAI-Bench 这样的基准正在出现，用于评估视觉语言模型的物理世界理解，但对生成动画的定性评估仍是主观的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Whalefishin/LLM_animation">GitHub - Whalefishin/LLM_animation: A showroom for various animations generated by large language models (LLM). Our method takes a rigged 3D model and produces novel animations specified via natural language descriptions in a matter of seconds. · GitHub</a></li>
<li><a href="https://arxiv.org/abs/2501.16411">[2501.16411] PhysBench: Benchmarking and Enhancing Vision ...</a></li>
<li><a href="https://github.com/SHI-Labs/physical-ai-bench">GitHub - SHI-Labs/physical-ai-bench: [CVPR 2026 Oral] PAI ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一：一些人批评动画质量和文本理解，而另一些人则为其辩护，认为它是物理世界理解的有用基准。也有人怀疑 LLM 是否专门针对 three.js 代码进行训练，使得此类输出不太能代表通用智能。

**标签**: `#LLM`, `#3D animation`, `#benchmark`, `#AI`, `#Karpathy`

---

<a id="item-14"></a>
## [中世纪《诺托里亚术》作为 AI 即时知识承诺的历史镜像](https://publicdomainreview.org/essay/ars-notoria/) ⭐️ 6.0/10

《公共领域评论》上的一篇文章将中世纪承诺通过天使魔法获得即时知识的《诺托里亚术》与现代 AI 的即时知识承诺相提并论。文章探讨了这一历史文本如何反映人类对快速学习和掌握的持久渴望。 这种比较为 AI 的文化影响提供了新视角，强调即时知识的承诺并非新鲜事物，而是深植于人类历史。它促使人们批判性反思 AI 的局限性以及寻求专业知识捷径的伦理影响。 《诺托里亚术》是一部归因于所罗门的中世纪魔法书，包含祈祷文和被认为能快速获得学术知识的“notae”（符号）。文章利用历史记载，如莫里尼的约翰的经历，来说明这种魔法捷径的诱惑和危险，并与现代 AI 工具如知识库进行类比。

hackernews · jruohonen · Aug 2, 10:18 · [社区讨论](https://news.ycombinator.com/item?id=49143001)

**背景**: 《诺托里亚术》是中世纪欧洲所罗门魔法传统的一部分，被学者用来快速掌握修辞学和辩证法等学科。现代 AI，特别是大型语言模型和知识管理系统，同样承诺即时获取信息和加速学习，引发了对知识本质和努力学习的价值的质疑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=vv0plm9SVIo">Ars Notoria - Medieval Magic for Learning All Knowledge... - YouTube</a></li>
<li><a href="https://www.youtube.com/watch?v=oAld-W9spEA">Ars Notoria [Solomonic Magic - Full Grimoire] - YouTube</a></li>
<li><a href="https://www.abebooks.com/9781644115275/Ars-Notoria-Notory-Art-Solomon-1644115271/plp">Ars Notoria : The Notory Art of Solomon: A Medieval ... - AbeBooks</a></li>

</ul>
</details>

**社区讨论**: 评论者认为历史类比有趣，但指出与 AI 的联系显得牵强或标题党。一些人讨论了“迦勒底”这一误称，以及这种魔法捷径的实际局限性，将其与现代物理或计算机科学等需要严谨性的领域进行对比。还有人幽默地将这本魔法书与《战锤 40k》的设定联系起来。

**标签**: `#history`, `#AI`, `#knowledge`, `#philosophy`, `#education`

---

<a id="item-15"></a>
## [MkLinux 在 Apple Workgroup Server 9150 上的怀旧故事](http://oldvcr.blogspot.com/2026/08/mklinux-and-pimped-out-apple-workgroup.html) ⭐️ 6.0/10

一篇博客文章讲述了作者在 Apple Workgroup Server 9150 上运行 MkLinux 的经历，详细描述了技术挑战和该机器的独特硬件。文章强调了 MkLinux 作为苹果首个开源项目的历史意义。 这段怀旧叙述揭示了苹果历史上拥抱开源软件的关键时刻，影响了其未来的操作系统战略。它与复古计算爱好者产生共鸣，并提供了对 PowerPC 硬件上 Linux 早期发展的洞察。 Apple Workgroup Server 9150 采用 Quadra 900 风格机箱，配备 80 MHz PowerPC 601 处理器（后提升至 120 MHz），内置磁带备份驱动器，并将软驱移至机箱底部。MkLinux 将 Linux 作为用户态服务器运行在 Mach 3.0 微内核之上，虽然稳定性好，但带来了性能开销。

hackernews · goldenskye · Aug 2, 03:12 · [社区讨论](https://news.ycombinator.com/item?id=49140702)

**背景**: MkLinux，即微内核 Linux，是一个实验性的开源操作系统，于 1995 年由开放软件基金会（OSF）和苹果电脑公司合作推出。它将 Linux 内核移植到 Mach 微内核之上，标志着苹果首个官方自由开源软件项目。Apple Workgroup Server 9150 是 1994 年发布的高端服务器型号，以其独特的机箱设计和 PowerPC 架构而著称。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MkLinux">MkLinux</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_Workgroup_Server_9150">Apple Workgroup Server 9150</a></li>
<li><a href="http://www.mklinux.org/">Welcome to MkLinux.org</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了在类似 Power Mac 上使用 MkLinux 的个人轶事，指出其相比 System 7 更稳定，但最初不支持多键鼠标。一些人表达了对那个时代的怀念，另一些人则强调了微内核架构带来的性能权衡。

**标签**: `#MkLinux`, `#Apple`, `#retrocomputing`, `#Linux`, `#PowerPC`

---

<a id="item-16"></a>
## [Greg Brockman：人们不喜欢同事的 ChatGPT 在 Slack 上联系自己](https://simonwillison.net/2026/Aug/1/greg-brockman/#atom-everything) ⭐️ 6.0/10

OpenAI 总裁兼联合创始人 Greg Brockman 观察到，在 OpenAI，许多员工将 ChatGPT 连接到 Slack，但人们非常不喜欢被同事的 ChatGPT 联系请求帮助，即使他们很乐意直接帮助那位同事。 这凸显了 AI 整合中一个关键的人本关切：AI 应该增强人际关系并节省时间，而不是成为分隔人们的层。它强调了设计尊重并增强工作场所人际联系的 AI 工具的重要性。 这一观察来自 Greg Brockman 的一条推文，由 Simon Willison 的博客分享。它反映了工作场所中 AI 中介通信的真实案例，其中 AI 作为中介，可能减少了感知到的人情味。

rss · Simon Willison · Aug 1, 22:29

**背景**: AI 在 Slack 等工作场所工具中的整合正变得越来越普遍，ChatGPT 提供了原生 Slack 集成用于摘要和协助。然而，这引发了关于 AI 中介通信的伦理问题，因为信任和人际关系是有效协作的基础。Brockman 的评论表明，虽然 AI 可能有用，但它不能取代互动中的人性元素。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://clearfeed.ai/blogs/chatgpt-slack-integration-guide">ChatGPT Slack Integration : What the App Does Well (and Where...)</a></li>
<li><a href="https://journals.sagepub.com/doi/10.1177/15480518241289644">Artificial Intelligence (AI) and Workplace Communication ...</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#human-AI interaction`, `#workplace AI`, `#OpenAI`, `#generative AI`

---