# Horizon 每日速递 - 2026-10-25

> From 10 items, 9 important content pieces were selected

---

1. [10 年前的 CNN 在皮肤癌诊断中击败前沿 LLM](#item-1) ⭐️ 7.0/10
2. [俄勒冈警方就一名警察的记录向新闻媒体收费 250 万美元](#item-2) ⭐️ 7.0/10
3. [加州大学伯克利分校数学教授因 AI 认为批改作业“没有意义”](#item-3) ⭐️ 7.0/10
4. [Dan Luu 关于软件雄心的文章引发 Hacker News 热议](#item-4) ⭐️ 7.0/10
5. [Cerebras 在晶圆级硬件上部署万亿参数模型](#item-5) ⭐️ 7.0/10
6. [小程序与语言：极简编码的反思](#item-6) ⭐️ 7.0/10
7. [FOSDEM 关于抵制互联网审查的演讲引发讨论](#item-7) ⭐️ 6.0/10
8. [Show HN：用员工火柴人可视化标普 500 市值气泡](#item-8) ⭐️ 6.0/10
9. [fheroes2：开源重制《魔法门之英雄无敌 II》游戏引擎](#item-9) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [10 年前的 CNN 在皮肤癌诊断中击败前沿 LLM](https://lynchlab.net/llm-skin-cancer) ⭐️ 7.0/10

Lynch Lab 的一篇博客文章报告称，一个已有 10 年历史的 Inception v3 卷积神经网络在来自 ISIC 档案的 68,011 张皮肤镜和临床图像上微调后，在 200 个病变的测试集上诊断皮肤癌的表现优于两个前沿大语言模型（LLM）。 这一结果表明，在医学图像分类等狭窄且高风险的任务上，专门化的小模型仍能超越规模大得多的通用 LLM，引发了对 LLM 能力评估方式及其最适用场景的质疑。 该 CNN 在单个 H100 GPU 上训练，测试病变（以及同一病变或患者的其他所有图像）被严格排除在训练和验证之外以防止数据泄漏；然而批评者认为，这种比较可能是一种“基准刷分”（benchmaxxing），因为 CNN 是专门针对该基准调优的，而 LLM 则不是。

hackernews · sungam · Oct 25, 17:15 · [社区讨论](https://news.ycombinator.com/item?id=50233779)

**背景**: Inception v3 是谷歌于 2015 年推出的卷积神经网络架构，以其高效性著称，并广泛用于医学成像的迁移学习。前沿 LLM 是最先进的通用语言模型，通常具备多模态能力，但它们并非专为皮肤病变诊断等细粒度图像分类任务而设计。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Inception_(deep_learning_architecture)">Inception (deep learning architecture) - Wikipedia</a></li>
<li><a href="https://llmsguru.com/glossary/frontier-model/">What is Frontier Model? Plain-English... | LLMs Guru AI Dictionary</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认为，专门化模型击败通用 LLM 并不令人意外，一些人指出 LLM 可以用来低成本地生成此类专门化模型。其他人则批评这种比较是“基准刷分”，并认为 LLM 在诊断中的潜力在于整合临床笔记等额外数据和交互式提问，而非原始图像分类。

**标签**: `#machine-learning`, `#medical-ai`, `#llm-comparison`, `#computer-vision`, `#benchmarking`

---

<a id="item-2"></a>
## [俄勒冈警方就一名警察的记录向新闻媒体收费 250 万美元](https://theintercept.com/2026/10/01/oregon-police-misconduct-public-records-cost-fee/) ⭐️ 7.0/10

俄勒冈州尤金警察局告知一家当地新闻媒体，处理一份关于一名警察的公共记录请求将需要至少 44,816 小时的员工时间，费用约为 2,484,599.04 美元。该请求旨在获取与一名警察相关的记录，因使用高昂费用阻碍信息获取而引发众怒。 这一案例揭示了利用过高费用来实质性地拒绝公共记录请求的日益增长的手段，损害了政府透明度以及记者调查警察不当行为的能力。它突显了公共记录法（如 FOIA）可能被滥用以向公众隐瞒信息的系统性问题。 估计的 44,816 小时相当于一名员工约 21 年的全职工作时间，使得该费用高得离谱且具有阻挠性。近 250 万美元的报价远远超出了大多数地方新闻编辑部的预算，实际上使该请求无法进行。

hackernews · tdeck · Oct 25, 18:04 · [社区讨论](https://news.ycombinator.com/item?id=50234232)

**背景**: 公共记录法，如联邦层面的《信息自由法》（FOIA）和类似的州法规，旨在让公民和记者能够获取政府文件。然而，机构可以对搜索、审查和复制记录收取费用，这些费用可能被用作障碍。警察不当行为记录往往尤其难以获取，许多州施加了严格的保密规定或高昂成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pulitzercenter.org/stories/police-misconduct-records-secret-difficult-access">Police Misconduct Records Secret, Difficult to Access | Pulitzer Center</a></li>
<li><a href="https://www.yahoo.com/news/city-detroit-wants-17-000-110309235.html">City of Detroit wants $17,000 to fill FOIA request on controversial...</a></li>

</ul>
</details>

**社区讨论**: 评论者对这一费用的荒谬性表示愤怒，其中一人指出 44,816 小时大约相当于 21 年的工作量。其他人分享了机构采用拖延战术的个人经历，例如每月部分发布记录，并将这种情况与英国的 FOIA 系统进行比较，称英国能在 30 天内提供信息且不收取过高费用。另一位评论者指出，与 2015 年国防部报价 1500 万小时和 6.6 亿美元的要求相比，这相对便宜。

**标签**: `#public records`, `#government transparency`, `#FOIA`, `#police misconduct`, `#journalism`

---

<a id="item-3"></a>
## [加州大学伯克利分校数学教授因 AI 认为批改作业“没有意义”](https://www.dailycal.org/news/campus/academics/ai-use-leads-uc-berkeley-math-professor-to-see-no-point-in-grading-homework/article_bdf1eae2-c08b-491f-b9f1-81a7cea177de.html) ⭐️ 7.0/10

加州大学伯克利分校数学教授、菲尔兹奖得主理查德·博切兹在观察到许多学生使用 AI 持续获得高分后，不再批改作业。 这凸显了 AI 如何挑战高等教育中的传统评估方法，引发了关于作业目的和需要新评估方法的讨论。 博切兹是菲尔兹奖得主，以证明“魔群月光”猜想而闻名，他通常将批改作业的任务交给助教，因此他的决定反映了对作业在学习中作用的更广泛反思。

hackernews · romanhn · Oct 25, 16:28 · [社区讨论](https://news.ycombinator.com/item?id=50233304)

**背景**: 理查德·博切兹是加州大学伯克利分校的数学家，因在魔群和模形式方面的工作于 1998 年获得菲尔兹奖。随着 ChatGPT 等工具使学生能够以最小努力完成作业，关于 AI 在教育中的争论愈演愈烈，引发了学术诚信和传统评分有效性的问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.dailycal.org/news/campus/academics/ai-use-leads-uc-berkeley-math-professor-to-see-no-point-in-grading-homework/article_bdf1eae2-c08b-491f-b9f1-81a7cea177de.html">AI use leads UC Berkeley math professor to see ‘no point’ in grading ...</a></li>

</ul>
</details>

**社区讨论**: 评论者就作业的目的展开辩论，一些人指出博切兹早已将批改作业委托给助教，颇具讽刺意味。其他人认为作业有助于学习，而 AI 消除了逐步练习的强制作用，还有人建议将掌握程度（考试）与认真程度（出勤）分开评估。

**标签**: `#AI in education`, `#grading`, `#academia`, `#assessment`, `#Hacker News`

---

<a id="item-4"></a>
## [Dan Luu 关于软件雄心的文章引发 Hacker News 热议](https://danluu.com/ambitious/) ⭐️ 7.0/10

Dan Luu 发表了一篇文章，主张软件开发者在构建项目时应更具雄心，该文章登上 Hacker News 首页，获得超过 700 分和 644 条评论。 这场讨论凸显了一个日益激烈的争论：AI 工具是让开发者能够着手更宏大的项目，还是助长了过拟合、难以维护的代码，反映了业界在软件质量与雄心方面的更广泛矛盾。 评论者分享了 AI 辅助的雄心项目的具体例子，例如开源硬件 AV1 视频解码器和 Kobo 电子墨水应用 SDK，但也有人警告说 LLM 生成的代码往往难以泛化且难以维护。

hackernews · ltratt · Oct 24, 21:47 · [社区讨论](https://news.ycombinator.com/item?id=50225695)

**背景**: Dan Luu 是一位知名的软件工程师和博主，经常撰写关于工程实践和行业趋势的文章。Hacker News 是一个流行的技术讨论论坛，文章常引发广泛辩论。大型语言模型（LLM）的兴起加剧了关于 AI 如何改变软件开发的讨论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Artificial_intelligence">Artificial intelligence - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hacker">Hacker - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：一些开发者称赞 AI 让他们终于能够构建因时间不足而搁置的雄心勃勃的副项目，而另一些人则警告 LLM 会产生混乱、过拟合的代码，损害可维护性和性能。还有少数评论者指出，科技圈之外的软件质量仍然很差，凸显了需要更具雄心的思考。

**标签**: `#software-engineering`, `#ambition`, `#AI`, `#Hacker News`, `#discussion`

---

<a id="item-5"></a>
## [Cerebras 在晶圆级硬件上部署万亿参数模型](https://www.cerebras.ai/blog/how-we-deploy-trillion-parameter-frontier-models-on-cerebras) ⭐️ 7.0/10

Cerebras 发布博客，详细介绍了如何在其晶圆级硬件上服务万亿参数的前沿 AI 模型，特别是如何将这些模型映射到 WSE-3 晶圆上，以实现每秒 1,000–2,000+ 个 token 的吞吐量。该公告在 Hacker News 上引发了 334 分、119 条评论的讨论，议题涉及速度、模型新鲜度和商业可持续性。 这表明晶圆级硬件能够以极高的推理速度服务最大的前沿模型，可能使实时 AI 应用更加可行。这也凸显了 Cerebras 在 AI 推理市场中的差异化，它需要与基于 GPU 的解决方案以及 Groq 等其他专业提供商竞争。 Cerebras 将万亿参数模型映射到其 WSE-3 晶圆上，晶圆被细分为二维的处理单元（PE）网格，这些单元以一致的时序向相邻核心流式传输数据。然而，社区成员指出，Cerebras 上实际可用的模型往往较旧或较小（例如 GPT OSS 120B、Qwen 3.8 27B），而且该公司在制造其巨型晶圆节点方面面临限制。

hackernews · gmays · Oct 25, 01:33 · [社区讨论](https://news.ycombinator.com/item?id=50227356)

**背景**: Cerebras Systems 开发晶圆级芯片，特别是 WSE（晶圆级引擎），它将整片硅晶圆作为一个芯片使用，以提供巨大的片上内存和计算能力。这种架构旨在通过将数据保留在片上并减少通信瓶颈来加速 AI 训练和推理。万亿参数模型是最大的神经网络之一，服务时需要巨大的内存和计算资源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cerebras.ai/blog/how-we-deploy-trillion-parameter-frontier-models-on-cerebras">How Cerebras Deploys Trillion - Parameter AI Models</a></li>
<li><a href="https://en.wikipedia.org/wiki/Cerebras_Systems">Cerebras Systems - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者就 Cerebras 的商业可行性展开辩论，一些人认为它缺乏满足需求的资金，必须提供廉价套餐来吸引客户。其他人批评该公司提供过时或能力较弱的模型，不过一些人预计它很快会以更低成本和更高速度提供更好的模型。少数人分享了复杂的专业体验，称赞技术但质疑团队是否足够优秀。

**标签**: `#cerebras`, `#ai-inference`, `#wafer-scale`, `#llm-serving`, `#hardware`

---

<a id="item-6"></a>
## [小程序与语言：极简编码的反思](https://ratfactor.com/cards/pl-small) ⭐️ 7.0/10

ratfactor.com 上的文章《小程序与语言》探讨了编写极小程序和极简语言的吸引力与技巧，在 Hacker News 上引发了 178 分、28 条评论的讨论。社区成员分享了具体例子，如 39 字节的十六进制解码器和一个引导加载程序大小的操作系统，并辩论了直接编译为机器码的利弊。 这场讨论凸显了代码高尔夫和极简编程作为加深对计算和语言设计理解的方式的持久吸引力，即使这些技术并不直接用于主流软件开发。它还展示了约束如何激发创造力和学习，激励开发者探索深奥语言和小程序。 社区示例包括 Uxn 中 39 字节的十六进制解码器、125 字节的 JSON 转 NDJSON 转换器、1024 字节的 BLAKE2s 实现，以及 1853 字节的带图形和声音的纸牌游戏。一位评论者提到了 Binary Lambda Calculus，其自解释器仅 168 位（21 字节），另一位则提议使用机器码作为字节码以简化编译。

hackernews · andsoitis · Oct 24, 21:44 · [社区讨论](https://news.ycombinator.com/item?id=50225674)

**背景**: 代码高尔夫是一种编程竞赛，参与者力求编写尽可能短的代码来完成给定任务。极简编程语言，如深奥语言（esolang），旨在测试语言设计的边界，通常优先考虑简单性或概念优雅性而非实用性。这些追求在黑客和学者中很受欢迎，作为创造力和对计算深入理解的练习。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Esoteric_programming_language">Esoteric programming language</a></li>
<li><a href="https://esolangs.org/">Esolang, the esoteric programming languages wiki</a></li>

</ul>
</details>

**社区讨论**: 讨论积极且投入，评论者分享了个人项目，如引导加载程序大小的操作系统和小型 Uxn 程序，并辩论了直接编译为机器码与字节码的优缺点。一些人表达了对底层编程的怀旧和重新燃起的兴趣，而另一些人则强调了 Binary Lambda Calculus 等理论构造。

**标签**: `#programming-languages`, `#code-golf`, `#minimalism`, `#compilers`, `#hacker-news`

---

<a id="item-7"></a>
## [FOSDEM 关于抵制互联网审查的演讲引发讨论](https://talkweb.eu/openweb/4558/) ⭐️ 6.0/10

即将举行的 FOSDEM 会议上一场题为“我拒绝接受被审查的互联网”的演讲公告已发布，并附带了 Hacker News 上的讨论，获得 240 分和 114 条评论，探讨了审查与内容审核的细微差别。 讨论凸显了在线言论自由与内容审核之间日益紧张的关系，以及无审查互联网的可行性，这影响着全球的开发者、活动人士和平台。 该演讲计划在 FOSDEM 27 上进行，这是布鲁塞尔一年一度的自由及开源软件会议，Hacker News 的讨论帖包含了关于审查是否不可避免以及基础设施提供商角色的观点。

hackernews · Tomte · Oct 25, 17:30 · [社区讨论](https://news.ycombinator.com/item?id=50233929)

**背景**: FOSDEM 是一个非商业、志愿者组织的年度会议，专注于自由及开源软件，在布鲁塞尔自由大学举行。互联网审查规避涉及绕过对在线内容的合法控制或压制的方法，而内容审核是筛选平台上用户生成内容的做法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/FOSDEM">FOSDEM</a></li>
<li><a href="https://en.wikipedia.org/wiki/Internet_censorship_circumvention">Internet censorship circumvention - Wikipedia</a></li>
<li><a href="https://www.institutmontaigne.org/en/expressions/challenges-content-moderation">Challenges of Content Moderation | Institut Montaigne</a></li>

</ul>
</details>

**社区讨论**: 评论者争论无审查互联网是否可能，一些人认为审核是一种审查形式因而不可避免，另一些人则批评演讲只关注某些国家而忽略了更广泛的问题。总体情绪褒贬不一，对演讲有兴趣，但对仅靠软件解决审查问题持怀疑态度。

**标签**: `#internet-censorship`, `#fosdem`, `#content-moderation`, `#privacy`, `#free-speech`

---

<a id="item-8"></a>
## [Show HN：用员工火柴人可视化标普 500 市值气泡](https://bigwhalehunting.com/workforce/) ⭐️ 6.0/10

一个 Show HN 项目将标普 500 公司可视化为市值气泡，并用火柴人代表员工数量，揭示了惊人的差异，例如英伟达每位员工对应 1.24 亿美元市值，而埃森哲的这一比率则低得多。 这种可视化提供了一种直观的方式来理解不同公司之间每位员工市值的巨大差异，并引发了关于此类指标能揭示商业模式和行业结构何种信息的讨论。 每个火柴人代表 1 万名员工，用户可以放大查看单个公司；然而，员工数量可能未完全涵盖兼职、季节性、合同工或特许经营员工，这可能会使比较结果出现偏差。

hackernews · vfxGer · Oct 25, 15:05 · [社区讨论](https://news.ycombinator.com/item?id=50232312)

**背景**: 标普 500 是一个按市值加权的指数，包含 500 家美国大型上市公司，这意味着市值越大的公司对指数表现的影响越大。每位员工市值是将公司总市值除以员工数量的指标，常用于衡量效率或比较商业模式，但若不了解劳动力构成，可能会产生误导。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Stock_market_index">Stock market index - Wikipedia</a></li>
<li><a href="https://www.spotmarketcap.com/blog/what-is-sp500-weighting">What is S & P 500 Weighting ? Index Construction... | SpotMarketCap</a></li>
<li><a href="https://www.linkedin.com/posts/tajventure-services-llc_nvidia-ai-techboom-activity-7359142121179705345-eTcT">Nvidia's $111M per employee : A market value metric , not... | LinkedIn</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，由于兼职、季节性、合同工以及特许经营模式的存在，员工数量并不简单，这可能会扭曲比较结果。还有人指出标普 500 分类的不一致之处，例如 Alphabet 和 Meta 被归类为通信服务而非信息技术，并对特斯拉和亚马逊等公司的分类进行了辩论。

**标签**: `#data-visualization`, `#S&P 500`, `#market-cap`, `#employment`, `#Show HN`

---

<a id="item-9"></a>
## [fheroes2：开源重制《魔法门之英雄无敌 II》游戏引擎](https://github.com/ihhub/fheroes2) ⭐️ 6.0/10

fheroes2 是一个开源项目，重新实现了《魔法门之英雄无敌 II》的游戏引擎，近日登上 Hacker News 首页，获得 184 分和 64 条评论。该项目允许玩家在需要原版游戏数据文件的前提下，以现代增强功能运行原版游戏。 该项目展示了开源逆向工程在保存经典游戏并使其在现代系统上可玩方面的价值，并促进了围绕复古游戏的社区互动。它还凸显了人们对《魔法门之英雄无敌》系列及相关项目（如 VCMI）的持续兴趣。 fheroes2 需要原版游戏的数据文件才能运行，并提供了更高分辨率和错误修复等改进。该项目使用 C++ 编写，在 GitHub 上积极维护，并提供了适用于 Windows、macOS 和 Linux 的构建指南。

hackernews · tosh · Oct 25, 11:09 · [社区讨论](https://news.ycombinator.com/item?id=50230384)

**背景**: 《魔法门之英雄无敌 II》是 New World Computing 于 1996 年发布的经典回合制策略游戏。像 fheroes2 和 VCMI（针对《英雄无敌 III》）这样的开源引擎重制项目，让玩家能在现代硬件上享受这些游戏并获得增强，但通常需要原版游戏资源以避免版权问题。此类项目依赖逆向工程来重新实现游戏逻辑，而不分发受版权保护的内容。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/ihhub/fheroes2">GitHub - ihhub/ fheroes2 : fheroes2 is a recreation of Heroes ...</a></li>
<li><a href="https://vcmi.eu/">Home - VCMI</a></li>
<li><a href="https://github.com/vcmi/vcmi">GitHub - vcmi / vcmi : Open-source engine for Heroes of Might ...</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了对该系列的怀旧之情，一些人指出游戏玩法对成年人来说可能已不再有趣。一位用户分享了使用 MCP 让 Claude 玩《英雄无敌 III》的实验，报告称 AI 表现不佳且速度缓慢。其他人提到了 VCMI 作为《英雄无敌 III》的替代引擎，并讨论了将 HoMM2 的画面与 HoMM3 的机制结合起来的梦想。

**标签**: `#game-engine`, `#open-source`, `#reverse-engineering`, `#retro-gaming`, `#heroes-of-might-and-magic`

---

