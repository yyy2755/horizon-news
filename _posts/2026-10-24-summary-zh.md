---
layout: default
title: "Horizon Summary: 2026-10-24 (ZH)"
date: 2026-10-24
lang: zh
---

> From 12 items, 10 important content pieces were selected

---

1. [HTTP2Shell Brotli 远程代码执行漏洞影响众多 HTTP 库](#item-1) ⭐️ 8.0/10
2. [OBS Studio 33 更新 CEF 修复已被利用的远程代码执行漏洞](#item-2) ⭐️ 7.0/10
3. [gpu-unlock 工具提升 Nvidia 3000 系列 GPU 的 FP/BF16 指令发射率](#item-3) ⭐️ 7.0/10
4. [构建 rqlite 十二年：分布式 SQLite 回顾](#item-4) ⭐️ 7.0/10
5. [纯函数式编程能有多接近 C 语言？](#item-5) ⭐️ 7.0/10
6. [Roku 将开发者仓库从 GitHub 迁移至 GitLab](#item-6) ⭐️ 6.0/10
7. [FreeDNS：长期免费的动态 DNS 服务在 Hacker News 上引发讨论](#item-7) ⭐️ 6.0/10
8. [丹麦政府悄然放弃开源办公软件试点](#item-8) ⭐️ 6.0/10
9. [物理学家 2018 年对量子诠释的批评引发 HN 辩论](#item-9) ⭐️ 6.0/10
10. [Simon Willison 用 Claude 生成的 Quick Study 将照片变成油画](#item-10) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [HTTP2Shell Brotli 远程代码执行漏洞影响众多 HTTP 库](https://www.aikido.dev/blog/python-packages-vulnerable-node2shell-brotli-cve-2026-111497) ⭐️ 8.0/10

一个被追踪为 CVE-2026-111497 的 Brotli 解压缩严重远程代码执行漏洞，最初被称为 Node2Shell，在研究人员发现其影响范围超出 Node.js、波及众多 HTTP 库和应用（包括使用 brotli 或 brotlicffi 的 Python 包）后，已更名为 HTTP2Shell。 该漏洞允许未经身份验证的远程代码执行，并影响大量支持 Brotli 压缩请求体的 HTTP 服务器和应用，可能使许多生产系统面临攻击风险。其广泛的影响范围以及修复数月未被认定为安全问题的状况，引发了对漏洞披露和补丁管理实践的担忧。 该漏洞特别影响那些解压攻击者可控 Brotli 数据的应用，虽然 HTTP 是最常见的攻击途径，但在其他场景中手动进行 Brotli 解码也可能存在风险。受影响的 Node.js 和 Python 包已发布补丁，但 Brotli 请求体支持在常见配置中的普及程度仍不明确。

hackernews · theanonymousone · Oct 24, 08:06 · [社区讨论](https://news.ycombinator.com/item?id=50219177)

**背景**: Brotli 是由 Google 开发的一种无损数据压缩算法，常用于 HTTP 中压缩响应，有时也用于压缩请求。远程代码执行（RCE）漏洞允许攻击者在目标系统上运行任意代码，通常会导致系统完全被攻陷。CVE-2026-111497 是分配给这个特定 Brotli 解压缩漏洞的编号，由于最初影响 Node.js 而被称为 Node2Shell。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aikido.dev/blog/node2shell-nodejs-brotli-rce-cve-2026-111497">Node 2 Shell : Node .js Brotli vulnerability allows remote code execution...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Brotli">Brotli - Wikipedia</a></li>
<li><a href="https://github.com/google/brotli">GitHub - google/brotli: Brotli compression format · GitHub</a></li>

</ul>
</details>

**社区讨论**: 评论者批评 HTTP2Shell 这个名称过于宽泛且没有意义，一些人更喜欢 Broccoli2Shell 或 Brotli2Shell 等替代名称。其他人则对如此多的实现支持 Brotli 压缩请求体感到惊讶，并质疑为什么该 RCE 在首次报告时未被认定为安全问题，暗示可能存在自动化流程的失误。

**标签**: `#security`, `#vulnerability`, `#brotli`, `#http`, `#rce`

---

<a id="item-2"></a>
## [OBS Studio 33 更新 CEF 修复已被利用的远程代码执行漏洞](https://github.com/obsproject/obs-studio/releases/tag/33.0.0) ⭐️ 7.0/10

OBS Studio 33.0.0 已发布，显著地将其 Chromium 嵌入式框架（CEF）运行时从版本 127/6533 更新到 150/7871。此更新修复了一个因 CEF 过时而存在的、已被积极利用的远程代码执行（RCE）漏洞。 对于广泛使用的开源直播工具来说，这是一个关键的安全修复，因为该漏洞已被积极利用并受到媒体关注。未更新的用户仍面临远程代码执行攻击的风险。 CEF 运行时大约过时了两年，而修复在漏洞利用引起公众关注约一个月后才到来。更新到 CEF 150/7871 使 OBS 与更新的 Chromium 版本保持一致，解决了已知漏洞。

hackernews · pentagrama · Oct 24, 04:49 · [社区讨论](https://news.ycombinator.com/item?id=50218430)

**背景**: OBS Studio 是一款免费开源的直播和屏幕录制软件。它使用 Chromium 嵌入式框架（CEF）来渲染基于浏览器的元素，如警报、聊天覆盖层和自定义浏览器源。CEF 基于 Chromium，因此保持其更新对安全至关重要，因为过时的版本可能包含可被恶意网页内容利用的已知漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/obsproject/obs-studio/releases">Releases · obsproject/ obs - studio</a></li>
<li><a href="https://chromiumembedded.github.io/cef/general_usage.html">CEF Documentation | Chromium Embedded Framework ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论对终于到来的 CEF 更新表示欣慰，一位用户指出该运行时已过时两年，且修复在漏洞被媒体报道一个月后才发布。其他人分享了使用 OBS 的积极体验，推荐了 VDO.ninja 等低延迟视频工具，并讨论了在 Linux 上的安装问题。

**标签**: `#OBS Studio`, `#security`, `#open-source`, `#streaming`, `#release`

---

<a id="item-3"></a>
## [gpu-unlock 工具提升 Nvidia 3000 系列 GPU 的 FP/BF16 指令发射率](https://github.com/Zagitta/gpu-unlock) ⭐️ 7.0/10

一个名为 gpu-unlock（由 Zagitta 开发）的新开源项目，通过利用 GPU 引导固件中的漏洞，允许用户在 Nvidia 3000 系列消费级 GPU（GA102、GA104、GA106）上解锁更高的 FP/BF16 指令发射率，实际上将 FP/BF16 FMA 到 FP32 操作的指令发射速度翻倍。社区成员报告在机器学习训练等任务中获得了 6-20%的实际加速，但该修改需要提高功耗限制和更好的散热。 这很重要，因为它绕过了 Nvidia 对消费级 GPU 施加的人为限制，可能为机器学习从业者和 GPU 爱好者提供免费的性提升，而无需购买新硬件。它突显了社区不断努力解锁消费级硬件中隐藏能力的行为，这可能影响 Nvidia 未来产品的设计以及用户优化现有设备的方式。 该解锁通过利用 GPU 引导固件中的经典缓冲区溢出漏洞实现，并以早期内核模块的形式提供，无需每次 Nvidia 发布新驱动时手动打补丁。然而，用户必须提高功耗限制（例如某些卡上高达 450W）并确保充分散热，因为更高的指令发射率会产生更多热量，可能超出原装散热器的能力。

hackernews · fragebogen · Oct 24, 09:58 · [社区讨论](https://news.ycombinator.com/item?id=50219700)

**背景**: Nvidia 的 3000 系列消费级 GPU（Ampere 架构）的硬件本可支持更高的 FP/BF16 指令发射率，但 Nvidia 在固件中人为限制了这一点，以区分消费级卡和专业型号。BF16（Brain Floating Point 16）是由 Google Brain 开发的 16 位浮点格式，因其在范围和精度上的平衡而被广泛用于机器学习。gpu-unlock 项目利用 GPU 引导程序中的漏洞绕过这一限制，类似于早期针对矿卡的 Windows 解锁方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Zagitta/gpu-unlock">GitHub - Zagitta/gpu- unlock · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bfloat16_floating-point_format">bfloat16 floating-point format - Wikipedia</a></li>
<li><a href="https://www.playground.ru/misc/news/entuziasty_snyali_iskusstvennoe_ogranichenie_nvidia_i_uskorili_videokarty_geforce_rtx_30_pochti_v_2_raza-1884221">Энтузиасты сняли искусственное ограничение NVIDIA и ускорили...</a></li>

</ul>
</details>

**社区讨论**: 社区反馈总体积极，用户报告在实际工作负载中获得了 6-20%的加速（例如在 3060 上训练速度提升 6%），并确认结果真实有效。然而，也有人提出了风险担忧：更高的功耗（高达 450W）、需要更好散热的更高温度，以及可能损坏显卡的风险。作者（Zagitta）参与讨论，澄清漏洞利用的想法并非原创，该工具只是将过程方便地打包；另一位用户提到一个相关的多 GPU 点对点加速补丁。

**标签**: `#GPU`, `#Nvidia`, `#performance`, `#overclocking`, `#machine-learning`

---

<a id="item-4"></a>
## [构建 rqlite 十二年：分布式 SQLite 回顾](https://philipotoole.com/twelve-years-of-distributed-sqlite/) ⭐️ 7.0/10

Philip O'Toole 发表了一篇回顾文章，总结了他十二年来开发 rqlite 的历程。rqlite 是一个基于 SQLite 的分布式系统，通过共识算法保持节点同步。该文章在 Hacker News 上引发了 345 分、51 条评论的热烈讨论，涉及生产可靠性、替代实现和权衡取舍。 这篇回顾为在 SQLite 之上构建容错分布式数据库的长期挑战提供了宝贵的工程见解，并凸显了 Cloudflare D1、Litestream 等分布式 SQLite 解决方案日益壮大的生态。对于在生产负载中选择嵌入式数据库还是服务器数据库的开发者来说，这篇文章具有重要意义。 rqlite 在节点之间使用共识算法（Raft）来保持同步并允许切换主节点，而 Litestream 只是将数据复制到 S3 以便另一节点接管。社区成员还指出，Cloudflare D1 构建在 Durable Objects 之上，在生产环境中可能不如直接使用 Durable Objects 可靠。

hackernews · otoolep · Oct 24, 01:16 · [社区讨论](https://news.ycombinator.com/item?id=50217500)

**背景**: SQLite 是一个广泛使用的嵌入式关系数据库，但它缺乏内置的分布式或复制功能。rqlite 通过将 SQLite 与 Raft 共识层结合来解决这个问题，从而实现容错和集群管理。Raft 是一种共识算法，设计为 Paxos 的可理解替代方案，确保集群中的所有节点对一系列状态转换达成一致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/rqlite/rqlite">rqlite / rqlite : The lightweight, fault-tolerant database built on SQLite .</a></li>
<li><a href="https://en.wikipedia.org/wiki/Raft_consensus_algorithm">Raft consensus algorithm</a></li>
<li><a href="https://raft.github.io/">Raft Consensus Algorithm</a></li>

</ul>
</details>

**社区讨论**: 评论者观点不一：有人表示 Cloudflare D1 在生产中不太可靠，并引用一位 D1 开发者的话说，通常直接使用 Durable Objects 更好；另一位描述了自己构建基于 Paxos 的多主 SQLite 实现（zaxonlite 和 sqlodin）；还有一位认为，借助现代工具管理 Postgres 已经足够简单，对于远程使用，SQLite 的局限性可能超过其简单性优势。

**标签**: `#distributed-systems`, `#sqlite`, `#databases`, `#rqlite`, `#consensus`

---

<a id="item-5"></a>
## [纯函数式编程能有多接近 C 语言？](https://rtfeldman.com/fp-vs-c) ⭐️ 7.0/10

Richard Feldman 的博客文章探讨了纯函数式编程语言与 C 语言之间的性能差距，并以 Roc 语言为例。文章认为，通过全程序优化和严格求值等技术，纯函数式编程在某些工作负载上可以达到与 C 相差 5% 以内的性能。 这一分析挑战了长期以来认为纯函数式编程为了安全性和表达力而必然牺牲性能的假设。对于选择性能关键型应用语言的开发者以及旨在减少高级抽象性能损失的语言设计者来说，这具有重要意义。 文章指出，Roc 的性能优势源于其严格求值策略、低开销运行时和全程序优化，这些特性消除了不必要的抽象。然而，比较仅限于特定基准测试，并且要达到这样的结果可能需要仔细的编码和编译器支持。

hackernews · stmonty · Oct 24, 03:43 · [社区讨论](https://news.ycombinator.com/item?id=50218195)

**背景**: 像 Haskell 和 Roc 这样的纯函数式编程语言强调不可变性和无副作用，这传统上会因复制和抽象而引入开销。C 语言以其低级控制和性能著称，通常作为性能比较的基准。近年来，编译器优化和运行时设计的进步缩小了这一差距，Roc 和 zlib-rs 等项目证明了这一点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dev.to/kornilovconstru/roc-vs-c-performance-evaluation-in-functional-programming-for-library-implementation-32n1">Roc vs. C: Performance Evaluation in Functional Programming ...</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了多个方面：jandrewrogers 指出 C/C++ 允许极端的复制消除，这对内存带宽至关重要；VorpalWay 指出将 Roc 的 lean-zip 与 miniz_oxide 比较不公平，并建议使用更快的 zlib-rs；WalterBright 提到了 D 语言的 `pure` 注解；andai 质疑在生产环境中使用不成熟的 Roc；gobdovan 询问是否可以通过库来暴露优化。

**标签**: `#functional-programming`, `#performance`, `#compilers`, `#language-design`, `#optimization`

---

<a id="item-6"></a>
## [Roku 将开发者仓库从 GitHub 迁移至 GitLab](https://blog.roku.com/developer/gitlab-move) ⭐️ 6.0/10

Roku 在其开发者博客上宣布，已将其开发者仓库从 GitHub 迁移至 GitLab。此次迁移影响 Roku 的内部和外部开发者工作流程，但公司未公开说明迁移原因。 此次迁移凸显了企业重新评估对 GitHub 依赖的趋势，尤其是在担心服务中断和平台锁定的背景下。它可能促使其他组织考虑 GitLab 的集成 DevOps 方案，从而影响更广泛的开发者工具生态系统。 Roku 的博客文章未提供太多技术细节，但此次迁移可能涉及仓库、CI/CD 流水线和问题跟踪的转移。GitLab 提供内置 CI/CD 和更集成的 DevOps 平台，这可能是一个决定因素。

hackernews · cxr · Oct 24, 16:06 · [社区讨论](https://news.ycombinator.com/item?id=50222622)

**背景**: GitHub 和 GitLab 都是基于 Web 的 Git 仓库管理器，但满足不同需求。GitHub 以其庞大的开源社区和社交编程功能闻名，而 GitLab 则强调一体化的 DevOps 平台，集成 CI/CD、安全和项目管理。企业通常根据工作流偏好、成本和可靠性考虑在两者之间选择。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.gitlab.com/ci/">Get started with GitLab CI / CD | GitLab Docs</a></li>
<li><a href="https://smartscope.blog/en/blog/cursor-origin-github-risk-2026/">GitHub Outages in 2026: A Resilience Plan and the... - SmartScope</a></li>
<li><a href="https://www.linkedin.com/pulse/choosing-right-git-repository-management-platform-github-vs-gitlab-6nk4f">Choosing the Right Git Repository Management Platform : GitHub vs ...</a></li>

</ul>
</details>

**社区讨论**: Hacker News 评论者讨论了利弊，一些人认为 GitLab 更适合企业项目并提供更优的 CI，而另一些人则质疑迁移时机是否与 GitHub 服务中断有关，并指出没有平台能完全避免宕机。还有人批评 Roku 未解释迁移原因，并指出开源项目要求 GitLab 账户的讽刺之处。

**标签**: `#gitlab`, `#github`, `#developer-tools`, `#platform-migration`, `#ci-cd`

---

<a id="item-7"></a>
## [FreeDNS：长期免费的动态 DNS 服务在 Hacker News 上引发讨论](https://freedns.afraid.org/) ⭐️ 6.0/10

Hacker News 上的一场讨论聚焦于 FreeDNS，这是一个拥有超过 700 万成员和 1380 万条记录的免费动态 DNS 服务，讨论重点是其可靠性以及诸如未列入公共后缀列表等安全注意事项。 FreeDNS 的巨大规模和长久运行表明了免费 DNS 托管服务的持续需求，但其未列入公共后缀列表引发了用户对共享域名安全性的担忧，影响了 cookie 隔离和整体网络安全。 FreeDNS 提供备份 DNS 和动态 DNS 功能，但其域名未列入公共后缀列表，可能导致 cookie 安全问题；讨论中还提到了 dns.he.net 和 nic.eu.org 等替代方案。

hackernews · esher · Oct 24, 15:20 · [社区讨论](https://news.ycombinator.com/item?id=50222133)

**背景**: 动态 DNS（DDNS）在 IP 地址变化时自动更新域名指向，允许远程访问具有动态 IP 的设备。公共后缀列表（PSL）是一个由社区维护的域名后缀列表，列出了独立组织可以注册网站的域名后缀，浏览器用它来执行 cookie 隔离等安全策略。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Public_Suffix_List">Public Suffix List</a></li>
<li><a href="https://en.wikipedia.org/wiki/FreeDNS">FreeDNS</a></li>
<li><a href="https://freedns.afraid.org/">FreeDNS - Free DNS - Dynamic DNS - Static DNS subdomain and ...</a></li>

</ul>
</details>

**社区讨论**: 评论者赞扬 FreeDNS 的长久性和可靠性，有人提到已使用近二十年。有人提出了其未列入公共后缀列表的安全担忧，用户还将其与 dns.he.net 和 nic.eu.org 等替代方案进行比较，并强调了其备份 DNS 功能。

**标签**: `#dns`, `#free-services`, `#web-security`, `#public-suffix-list`, `#hackernews`

---

<a id="item-8"></a>
## [丹麦政府悄然放弃开源办公软件试点](https://www.computerworld.dk/art/297226/digitaliseringsministeriet-har-i-al-stilhed-droppet-stort-anlagt-forsoeg-med-open-source-alternativ-til-microsoft) ⭐️ 6.0/10

丹麦数字政府机构已悄然放弃 2025 年春季启动的用 Collabora 替代 Microsoft Office 的试点项目，既没有进行评估，也没有重启计划。该项目在大选宣布后被无限期搁置，该机构未公布任何后续步骤。 这一挫折凸显了政府通过开源替代方案实现数字主权的挑战，并可能打击其他国家类似举措的积极性。它也表明，尽管开源倡导多年，专有软件在公共行政中的主导地位依然稳固。 该试点涉及 38 名测试用户，他们反馈了 Collabora 在排版和修订跟踪功能方面的问题。该机构未发布任何正式评估，因此除选举相关的暂停外，放弃该项目的具体原因尚不清楚。

hackernews · lowkeyokay · Oct 24, 18:31 · [社区讨论](https://news.ycombinator.com/item?id=50223844)

**背景**: Collabora Online 是一款基于 LibreOffice 的开源办公套件，常被定位为面向政府和企业的隐私优先的 Microsoft Office 替代品。数字主权是指政府独立于外国技术提供商控制其数字基础设施和数据的能力。丹麦一直积极推动数字政府举措，包括最近推出数字身份钱包 AltID。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Collabora_Online">Collabora Online - Wikipedia</a></li>
<li><a href="https://www.collaboraonline.com/collabora-office/">Collabora Office - Collabora Online and Collabora Office</a></li>
<li><a href="https://en.digst.dk/digital-governance/new-technologies/danish-strategies-for-artificial-intelligence/?trk=article-ssr-frontend-pulse_little-text-block">Danish strategies for artificial intelligence</a></li>

</ul>
</details>

**社区讨论**: 评论者对政府的开源承诺表示怀疑，指出几十年来类似声明从未兑现。一些人分享了 LibreOffice 可用性的实际困扰，例如标签邮件合并功能，另一些人则对此事发表了讽刺性评论。

**标签**: `#open-source`, `#government-it`, `#digital-sovereignty`, `#collabora`, `#microsoft-office`

---

<a id="item-9"></a>
## [物理学家 2018 年对量子诠释的批评引发 HN 辩论](https://www.southampton.ac.uk/~doug/quantum_physics/index.html) ⭐️ 6.0/10

南安普顿大学一位研究人员 2018 年发表的文章表达了对量子物理的困惑，并批评了多世界等诠释，近日在 Hacker News 上重新引发热议，获得 170 条评论。讨论主要集中在纠正对贝尔定理的误解，并推荐《Picturing Quantum Processes》和《QFT for the Gifted Amateur》等书籍。 这篇文章和讨论凸显了量子力学持续存在的概念挑战，以及公众准确理解贝尔定理等基础成果的重要性。此类辩论有助于澄清常见误解，并引导学习者找到可靠资源。 评论者指出，文章延续了对贝尔定理及其对隐变量理论含义的误解，并引用 Scholarpedia 文章进行深入讨论。其他人分享了通过物质波干涉和原子双缝实验等实验逐渐接受量子力学的个人经历。

hackernews · rramadass · Oct 24, 09:53 · [社区讨论](https://news.ycombinator.com/item?id=50219666)

**背景**: 量子力学描述微观尺度下的自然现象，已被无数实验证实，但其诠释——如哥本哈根诠释和多世界诠释——仍存在争议。贝尔定理表明量子力学与局域隐变量理论不相容，排除了某些经典解释。多世界诠释认为宇宙会为每个量子结果分裂成多个分支，但批评者认为其缺乏解释力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bell's_theorem">Bell's theorem - Wikipedia</a></li>
<li><a href="https://plato.stanford.edu/entries/bell-theorem/">Bell’s Theorem - Stanford Encyclopedia of Philosophy</a></li>

</ul>
</details>

**社区讨论**: 评论者总体上欣赏这篇文章，但纠正了其对贝尔定理的处理，其中一人链接到包含贝尔本人对误解感到沮丧的 Scholarpedia 文章。其他人推荐了适合视觉学习者的《Picturing Quantum Processes》和适合自学的《QFT for the Gifted Amateur》，也有人对作者难以接受多世界诠释表示同情。

**标签**: `#quantum physics`, `#interpretations`, `#Bell's theorem`, `#education`, `#discussion`

---

<a id="item-10"></a>
## [Simon Willison 用 Claude 生成的 Quick Study 将照片变成油画](https://simonwillison.net/2026/Oct/23/quick-study-painter/) ⭐️ 6.0/10

Simon Willison 发布了 Quick Study，这是一个基于 Claude Opus 5.5 High 单条提示词生成的浏览器工具，能利用 canvas 元素和模拟画笔快速将上传的照片渲染成模拟油画。该工具依赖 Sobel 边缘检测，除 Google Fonts 外不使用任何外部库。 这表明单条自然语言提示词就能生成一个完整、自包含且包含真实图像处理逻辑的创意编程产物，降低了构建交互式视觉工具的门槛。这也凸显了 Claude Opus 5.5 等模型在生成精致、依赖极少的浏览器应用方面日益增强的能力。 该工具使用 Sobel 边缘检测来引导模拟笔触，完全在浏览器中运行，唯一的外部依赖是 Google Fonts。它是一个小型个人实验而非生产级工具，提示词要求在大约几秒内完成渲染。

rss · Simon Willison · Oct 23, 21:35

**背景**: Sobel 边缘检测是一种经典的计算机视觉算子，通过估计图像水平和垂直方向的强度变化来寻找边缘，常被用作风格化渲染的基础构件。Claude Artifacts 是 Claude 在对话旁生成的自包含交互式产物（如小工具或动画），可通过链接分享。Simon Willison 此前也探索过类似的 AI 生成视觉实验，包括用 Claude Fable 和 P5.js 构建的水彩模拟。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.com/features/artifacts">Claude Artifacts | Claude by Anthropic</a></li>
<li><a href="https://9to5mac.com/2026/09/22/anthropic-upgrades-claude-with-new-opus-5-5-model-details-here/">Anthropic upgrades Claude with new Opus 5 . 5 model... - 9to5Mac</a></li>

</ul>
</details>

**标签**: `#AI-generated-code`, `#canvas`, `#image-processing`, `#Sobel-edge-detection`, `#creative-tools`

---