---
layout: default
title: "Horizon Summary: 2026-06-14 (ZH)"
date: 2026-06-14
lang: zh
---

> From 15 items, 11 important content pieces were selected

---

1. [Pyodide 314.0 支持直接将 WASM 轮子发布到 PyPI](#item-1) ⭐️ 9.0/10
2. [里约热内卢自研大语言模型被指为权重合并产物](#item-2) ⭐️ 8.0/10
3. [Jane Street 在生产中应用形式化方法的经验](#item-3) ⭐️ 8.0/10
4. [2014 年关于 JavaScript 兴衰的演讲回顾](#item-4) ⭐️ 8.0/10
5. [AI 采用率比炒作所暗示的更复杂](#item-5) ⭐️ 7.0/10
6. [如何赚到十亿美元](#item-6) ⭐️ 7.0/10
7. [将 SQLite 结果列映射回源表](#item-7) ⭐️ 7.0/10
8. [Kage：将任意网站打包成单个二进制文件供离线查看](#item-8) ⭐️ 6.0/10
9. [Zeroserve 声称与 Caddy 兼容后吞吐量提升 3 倍，延迟降低 70%](#item-9) ⭐️ 6.0/10
10. [艾伦·佩利斯的编程格言在 HN 上重现](#item-10) ⭐️ 6.0/10
11. [Linux 7.1 移除旧驱动以减少 AI 错误报告](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Pyodide 314.0 支持直接将 WASM 轮子发布到 PyPI](https://simonwillison.net/2026/Jun/13/publishing-wasm-wheels/#atom-everything) ⭐️ 9.0/10

Pyodide 314.0 允许 Python 包维护者使用 PEP 783 中定义的 PyEmscripten 平台标签，直接将 WebAssembly (WASM) 轮子发布到 PyPI。此前，Pyodide 维护者必须手动构建并托管超过 300 个包。 这消除了 Python 在浏览器中运行的主要瓶颈，使任何包作者都可以分发 WASM 轮子，而无需等待 Pyodide 维护者。这极大地扩展了在 Pyodide 等基于浏览器的环境中可用的 Python 包生态系统。 该功能基于 PEP 783（定义了 PyEmscripten 平台标签）以及 4 月 21 日合并到 PyPI 仓库的 PR。cibuildwheel 和 pyodide-build 等工具现在支持构建和上传这些轮子。

rss · Simon Willison · Jun 13, 23:55

**背景**: Pyodide 是 CPython 到 WebAssembly/Emscripten 的移植，允许 Python 在浏览器中运行。此前，将包含 C 或 Rust 扩展的 Python 包作为 WASM 轮子分发需要手动托管，且不受 PyPI 支持。PEP 783 为基于 Emscripten 的 Python 运行时标准化了平台标签。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/13/publishing-wasm-wheels/">Publishing WASM wheels to PyPI for use with Pyodide</a></li>
<li><a href="https://peps.python.org/pep-0783/">PEP 783 – Emscripten Packaging | peps.python.org</a></li>
<li><a href="https://discuss.python.org/t/pep-783-emscripten-packaging-is-accepted/107393">PEP 783 – Emscripten Packaging is accepted - WebAssembly - Discussions on Python.org</a></li>

</ul>
</details>

**社区讨论**: 文章引用的 Hacker News 讨论显示出强烈的积极情绪，许多用户对减轻维护负担以及更多 Python 包进入浏览器的潜力感到兴奋。一些评论者指出了 PEP 783 的重要性以及这一变化背后的协作努力。

**标签**: `#Pyodide`, `#WASM`, `#Python`, `#PyPI`, `#WebAssembly`

---

<a id="item-2"></a>
## [里约热内卢自研大语言模型被指为权重合并产物](https://github.com/nex-agi/Nex-N2/issues/4) ⭐️ 8.0/10

里约热内卢声称自研的大语言模型 Rio-3.5-Open-397B 被发现是约 60% Nex-N2 Pro 和 40% Qwen3.5-397B-A17B 的权重合并，而非所宣称的微调模型。 这一事件凸显了 AI 模型开发中缺乏透明度的问题，并引发了对开源 AI 中归属和虚假陈述的伦理担忧，可能削弱对声称创新的信任。 分析显示，Rio 模型中的每个权重张量在所有 60 层中都是 Nex 和 Qwen 的 0.6/0.4 混合，没有额外训练或蒸馏的证据。

hackernews · unrvl22 · Jun 14, 15:37 · [社区讨论](https://news.ycombinator.com/item?id=48528371)

**背景**: 模型合并是一种无需额外训练即可组合两个或多个预训练模型权重的技术，常用于融合能力。这种做法日益流行，但若未适当披露，可能导致归属问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2212.09849">[2212.09849] Dataless Knowledge Fusion by Merging Weights of Language Models</a></li>
<li><a href="https://arxiv.org/abs/2408.07666">[2408.07666] Model Merging in LLMs, MLLMs, and Beyond: Methods...</a></li>
<li><a href="https://medium.com/@jonathan.raia40/model-merge-and-its-methods-c9b3e7ba8d96">Supercharging Large Language Models through Model Merging | by Jonathan Rai | Medium</a></li>

</ul>
</details>

**社区讨论**: 社区评论对声称的自研开发表示怀疑，一些人指出缺乏披露以及可能从他人工作中获利。其他人则讨论模型合并的技术方面及其鲁棒性。

**标签**: `#AI`, `#open-source`, `#model merging`, `#ethics`, `#LLM`

---

<a id="item-3"></a>
## [Jane Street 在生产中应用形式化方法的经验](https://blog.janestreet.com/formal-methods-at-jane-street-index/?from_theconsensus=1) ⭐️ 8.0/10

Jane Street 发布了一篇博客文章，总结了他们十年来将形式化方法集成到生产系统中的经验，强调了实际收益和挑战。 这表明形式化方法可以在量化交易等高要求环境中实际应用，可能推动软件行业更广泛地采用。 该博客是一个系列的一部分，涵盖使用 OCaml 的类型系统进行验证以及将 SAT 求解器集成到开发工作流等主题。

hackernews · eatonphil · Jun 14, 12:35 · [社区讨论](https://news.ycombinator.com/item?id=48526633)

**背景**: 形式化方法是用于规范、开发和验证软件与硬件系统的数学严谨技术，旨在证明正确性而非仅依赖测试。Jane Street 是一家量化交易公司，一直是 OCaml 和形式化方法在生产中的著名用户。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Formal_methods">Formal methods - Wikipedia</a></li>
<li><a href="https://blog.janestreet.com/formal-methods-at-jane-street-index/">Jane Street Blog - Formal methods and the future of programming</a></li>
<li><a href="https://news.ycombinator.com/item?id=48526633">Formal Methods and the Future of Programming | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了使用形式化方法的经验，有人指出定理证明需要大量人力投入，也有人争论形式化规范是否只是另一种形式的测试。讨论还涉及 AI 在将人力转向验证方面的作用。

**标签**: `#formal methods`, `#programming`, `#verification`, `#Jane Street`, `#software engineering`

---

<a id="item-4"></a>
## [2014 年关于 JavaScript 兴衰的演讲回顾](https://www.destroyallsoftware.com/talks/the-birth-and-death-of-javascript) ⭐️ 8.0/10

Gary Bernhardt 在 2014 年的一次演讲预测了 JavaScript 作为编译目标的统治地位及其最终被取代，如今该演讲重新引起关注，社区反思 WebAssembly 和 TypeScript 如何部分实现了这一愿景。 该演讲的预测在今天极具相关性，因为 WebAssembly 日趋成熟，TypeScript 变得无处不在，凸显了 Web 开发的持续演进以及 JavaScript 作为编译目标的角色。 该演讲特别提到了 asm.js 作为早期的编译目标，后来已被 WebAssembly 取代；TypeScript 作为 JavaScript 的类型超集，也已成为一种编译到 JavaScript 的主要语言。

hackernews · subset · Jun 14, 12:38 · [社区讨论](https://news.ycombinator.com/item?id=48526661)

**背景**: JavaScript 最初被设计为浏览器的简单脚本语言，但其普及性促使人们将其用作其他语言的编译目标。Asm.js 是早期尝试，通过将 C/C++编译为 JavaScript 的子集来实现接近原生的性能，但后来被 WebAssembly 取代，WebAssembly 是一种为高效执行和紧凑表示而设计的二进制指令格式。TypeScript 由微软开发，为 JavaScript 添加了静态类型，并编译为普通 JavaScript，提高了大型应用程序的开发效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly - Wikipedia</a></li>
<li><a href="https://webassembly.org/">WebAssembly</a></li>
<li><a href="https://github.com/appcypher/awesome-wasm-langs">GitHub - appcypher/awesome-wasm-langs: 😎 A curated list of languages that compile directly to or have their VMs in WebAssembly</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，该演讲准确预测了 2020-2025 年间的一场全球灾难，只是类型不对。一些人观察到 WebAssembly 的改进速度不如预期，缺乏直接的 DOM 访问，因此 JavaScript 仍然需要作为胶水代码。其他人则强调 TypeScript 和 Electron 已将 Web 技术扩展到桌面应用。

**标签**: `#JavaScript`, `#WebAssembly`, `#Programming Languages`, `#History`, `#Tech Predictions`

---

<a id="item-5"></a>
## [AI 采用率比炒作所暗示的更复杂](https://gabrielweinberg.com/p/people-are-consuming-ai-like-they) ⭐️ 7.0/10

最近一篇文章指出，尽管 AI 炒作盛行，但许多人并未广泛使用 AI，实际采用情况比宣传的更复杂和谨慎。文章引用了一项研究，显示超过 50%的人每周使用 AI 不到一次。 这挑战了 AI 已被普遍采用的主流叙事，凸显了炒作与现实之间的差距，对规划 AI 集成的企业、政策制定者和技术专家至关重要。它也强调了需要细致理解用户行为和工作场所动态。 文章指出，AI 使用通常通过自我报告频率来衡量，这可能忽略了现有软件中嵌入的 AI 功能。社区评论显示，雇主在面试中询问 LLM 的使用情况，用户发现 AI 对编码有帮助但需要监督。

hackernews · yegg · Jun 14, 14:44 · [社区讨论](https://news.ycombinator.com/item?id=48527700)

**背景**: AI 采用一直是一个热门话题，许多人声称每个人都在使用 ChatGPT 等 AI 工具。然而，实际使用数据表明情况更加分散，有些人大量使用 AI，而另一些人很少或从不使用。这篇文章提供了对炒作的反驳。

**社区讨论**: 评论者分享了不同的体验：有人指出雇主在面试中期望 AI 知识，而另一些人则认为 AI 集成缓慢且被过度炒作。一个关键见解是，AI 采用可能通过嵌入式功能而非独立聊天界面增长。

**标签**: `#AI adoption`, `#technology skepticism`, `#workplace`, `#LLMs`, `#hacker news`

---

<a id="item-6"></a>
## [如何赚到十亿美元](https://paulgraham.com/earn.html) ⭐️ 7.0/10

保罗·格雷厄姆发表了一篇文章，认为创建一家十亿美元级别的初创公司需要解决一个罕见且可扩展的问题，并打造出人们想要的产品。 这篇文章引发了关于财富创造和不平等的讨论，影响了创业文化和风险投资思维。 文章强调，十亿美元的财富来自于大规模创造价值，而非零和博弈的榨取。

hackernews · kingstoned · Jun 14, 11:50 · [社区讨论](https://news.ycombinator.com/item?id=48526360)

**背景**: 保罗·格雷厄姆是知名风险投资家，也是创业加速器 Y Combinator 的联合创始人。他的文章常常塑造创业者的思维方式。

**社区讨论**: 评论褒贬不一：有人为格雷厄姆的现实观点辩护，也有人批评财富集中，认为亿万富翁往往剥削劳动力。

**标签**: `#startups`, `#wealth`, `#entrepreneurship`, `#venture capital`

---

<a id="item-7"></a>
## [将 SQLite 结果列映射回源表](https://simonwillison.net/2026/Jun/13/sqlite-column-provenance/#atom-everything) ⭐️ 7.0/10

Simon Willison 探索了在任意 SQL 查询中，通过编程方式识别每个结果列的源 table.column 的技术，并借助 Claude Code 找到了使用 apsw、ctypes 和 EXPLAIN 分析的解决方案。 这一能力将使 Datasette 能够为查询结果添加列级元数据，从而改善数据探索体验和 SQL 工具的功能。 解决方案包括使用 apsw 库、通过 ctypes 访问 SQLite 的 C 函数 sqlite3_column_table_name()，以及解析 EXPLAIN 输出。由于 Fable 被美国政府禁用，该工作使用了 Claude Code (Opus 4.8) 完成。

rss · Simon Willison · Jun 13, 23:05

**背景**: Datasette 是一个用于探索和发布关系型数据库的工具。SQL 查询通常涉及连接和 CTE，这使得确定每个结果列来自哪个源表变得复杂。SQLite 的 C API 提供了如 sqlite3_column_table_name() 等函数，但这些函数在 Python 的标准 sqlite3 模块中并未暴露。

**标签**: `#SQL`, `#Datasette`, `#database`, `#AI-assisted development`

---

<a id="item-8"></a>
## [Kage：将任意网站打包成单个二进制文件供离线查看](https://github.com/tamnd/kage) ⭐️ 6.0/10

Kage 是一款新的开源工具，能将任意网站打包成单个二进制可执行文件以供离线查看，用户无需网络连接即可提供和浏览存档的网站。 该工具简化了文档、维基和其他网页内容的离线访问，对于网络受限或无网络连接的场景（如野外工作或航空旅行）非常有价值。 Kage 创建一个包含所有站点资源的静态二进制文件，但需要内置服务器来提供内容；它不会生成可直接在浏览器中打开的单个 HTML 文件。

hackernews · tamnd · Jun 14, 17:25 · [社区讨论](https://news.ycombinator.com/item?id=48529990)

**背景**: 像 SingleFile 和 HTTrack 这样的离线网站存档工具早已存在，但 Kage 将站点打包成单个二进制文件的方法很新颖。该二进制文件既充当存档又充当服务器，简化了分发和执行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48529990">Show HN: Kage – Shadow any website to a single binary for offline viewing | Hacker News</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的社区评论显示了对离线公司维基等实际用例的兴趣，但也提出了与 SingleFile 和 HTTrack 等替代方案的比较。一些用户质疑静态内容是否需要服务器，并建议改进，例如使用单个 HTML 入口点。

**标签**: `#offline`, `#archiving`, `#web`, `#tool`, `#static-site`

---

<a id="item-9"></a>
## [Zeroserve 声称与 Caddy 兼容后吞吐量提升 3 倍，延迟降低 70%](https://su3.io/posts/zeroserve-caddy-compat) ⭐️ 6.0/10

Zeroserve，一个使用 eBPF 和 io_uring 的零配置 Web 服务器，宣布与 Caddy 兼容，相比标准 Caddy 实现了 3 倍吞吐量和 70% 的延迟降低。 这展示了 io_uring 和 eBPF 在 Web 服务方面的潜力，但缺乏 ACME 和插件支持限制了其大多数用户的实际使用。 兼容性是通过 Caddy 模块实现的，但不支持 ACME 自动证书管理或 Caddy 插件，而这些是许多部署的核心功能。

hackernews · losfair · Jun 14, 13:43 · [社区讨论](https://news.ycombinator.com/item?id=48527145)

**背景**: Zeroserve 是一个用 Rust 编写的高性能 Web 服务器，利用 Linux 的 io_uring 进行异步 I/O 和 eBPF 进行数据包处理。Caddy 是一个流行的 Web 服务器，以其通过 ACME 自动管理 HTTPS 而闻名。io_uring 是 Linux 内核中用于高效异步 I/O 的接口，但在某些情况下引发了安全担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Io_uring">Io uring</a></li>
<li><a href="https://sesamedisk.com/zeroserve-ebpf-web-server-infrastructure/">Zeroserve : An eBPF-Powered Web Server Without... - Sesame Disk</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些用户指出缺乏 ACME 支持是致命缺陷，而另一些用户则质疑 io_uring 用于 Web 服务器的安全性。一位评论者还观察到 NGINX 在基准测试中仍然表现良好。

**标签**: `#web server`, `#performance`, `#io_uring`, `#Caddy`, `#Rust`

---

<a id="item-10"></a>
## [艾伦·佩利斯的编程格言在 HN 上重现](https://www.cs.yale.edu/homes/perlis-alan/quotes.html) ⭐️ 6.0/10

艾伦·佩利斯（Alan Perlis）于 1982 年发表的一系列格言（称为“Perlisisms”）在 Hacker News 上被分享，引发了程序员们的讨论。 佩利斯的格言提供了关于编程、语言设计和思维本质的永恒见解，几十年后仍然具有现实意义，尤其是在大语言模型时代。 该合集包含 120 条格言，例如“不影响你思考编程方式的语言不值得学习”。其中一些格言被认为与现代 AI 和自然语言处理特别相关。

hackernews · tosh · Jun 14, 14:56 · [社区讨论](https://news.ycombinator.com/item?id=48527820)

**背景**: 艾伦·佩利斯是计算机科学先驱、首位图灵奖得主，也是早期编程语言设计（ALGOL）的关键人物。他的《编程格言》是一组关于软件开发的简洁、诙谐的观察，已成为经典参考文献。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Alan_Perlis">Alan Perlis</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了他们最喜欢的格言，其中一位指出有几条格言似乎对 LLM 有先见之明。另一位用户购买了域名 perl.is 来展示这些格言，还有几位最初将“Perlisisms”误读为“Perlism”。

**标签**: `#programming`, `#quotes`, `#history`, `#philosophy`

---

<a id="item-11"></a>
## [Linux 7.1 移除旧驱动以减少 AI 错误报告](https://lore.kernel.org/lkml/CAHk-=wi4BF4bMhZNZ1tqs+FFV4OuZRe3ZqdWB+LxRLmRweUzQw@mail.gmail.com/T/#u) ⭐️ 6.0/10

Linux 内核 7.1 已发布，显著移除了如 ISDN 和其他旧网络驱动等过时的驱动代码，以减少针对极少使用的硬件的 AI 生成错误报告。 此版本突显了一个新兴趋势：AI 辅助的错误报告促使内核维护者清理遗留代码，可能提高内核的可维护性并减少开发者的干扰。 移除的目标是如今很少使用的硬件驱动，例如 ISDN，这些驱动常常是低质量 AI 生成错误报告的来源。这是一项主动精简维护的措施。

hackernews · berlianta · Jun 14, 16:01 · [社区讨论](https://news.ycombinator.com/item?id=48528729)

**背景**: Linux 内核版本采用主版本号.次版本号.补丁号的方案；升级到 7.1 是 7.0 积累足够补丁后的常规递增。AI 辅助的错误报告工具越来越常见，有时会为过时代码生成虚假或不相关的报告。

**社区讨论**: 评论者普遍支持移除，有人称其为“AI 带来的最佳后果之一”，有助于精简内核。其他人则调侃稳定发行版（如 Debian）的缓慢采用，还有用户质疑版本号提升的意义。

**标签**: `#Linux`, `#kernel`, `#AI`, `#open source`

---