# Horizon 每日速递 - 2026-06-22

> From 27 items, 19 important content pieces were selected

---

1. [Valve 发布开放硬件 Steam Machine](#item-1) ⭐️ 9.0/10
2. [近半数 LG 智能电视应用使用住宅代理 SDK](#item-2) ⭐️ 8.0/10
3. [Moebius：0.2B 参数修补模型声称达到 10B 级性能](#item-3) ⭐️ 8.0/10
4. [Codex 日志漏洞可能向本地 SSD 写入 TB 级数据](#item-4) ⭐️ 8.0/10
5. [警察局长利用 Flock 车牌识别系统跟踪女性引发搜查令争议](#item-5) ⭐️ 8.0/10
6. [2025 年 Linux 安全启动证书到期](#item-6) ⭐️ 8.0/10
7. [Mitchell Hashimoto 向 Zig 软件基金会承诺捐赠 40 万美元](#item-7) ⭐️ 8.0/10
8. [Claude Code 的扩展思考是带损摘要](#item-8) ⭐️ 8.0/10
9. [雪佛龙与微软签署 20 年天然气供电协议](#item-9) ⭐️ 8.0/10
10. [PP-OCRv6 在 Hugging Face 发布，支持 50 种语言](#item-10) ⭐️ 8.0/10
11. [OpenAI 推出 Daybreak 安全工具](#item-11) ⭐️ 8.0/10
12. [Oak：为 AI 代理打造的 Git 替代品](#item-12) ⭐️ 7.0/10
13. [加拿大计划 15 年内新建多达 10 座核反应堆](#item-13) ⭐️ 7.0/10
14. [GLM 5.2 与 Opus 对比：基准测试争议升温](#item-14) ⭐️ 7.0/10
15. [Deno Desktop 支持多后端构建桌面应用](#item-15) ⭐️ 7.0/10
16. [sqlite-utils 4.0rc1 增加迁移和嵌套事务](#item-16) ⭐️ 7.0/10
17. [OpenAI 推出 Patch the Planet 助力开源安全](#item-17) ⭐️ 7.0/10
18. [Codex 在长期项目中的技巧](#item-18) ⭐️ 6.0/10
19. [AI 周报#120：SpaceX 收购 Cursor、GLM 5.2 发布、Shazeer 跳槽 OpenAI](#item-19) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Valve 发布开放硬件 Steam Machine](https://store.steampowered.com/news/group/45479024/view/685257114654870245) ⭐️ 9.0/10

Valve 于 2026 年 6 月 22 日正式发布新款游戏 PC Steam Machine，采用开放硬件设计，并引入随机预约系统以对抗机器人和黄牛。 此次发布强化了 Valve 对开放平台和 Linux 游戏的支持，可能通过提供兼具主机体验和 PC 灵活性的产品，改变 PC 游戏格局。 Steam Machine 采用持续数天的随机预约顺序以确保公平，用户可安装任何应用或操作系统，这与大多数主机不同。

hackernews · theschwa · Jun 22, 17:09 · [社区讨论](https://news.ycombinator.com/item?id=48632884)

**背景**: Steam Machine 是 Valve 继 Steam Deck 后的最新硬件产品，旨在将 PC 游戏带入客厅。它运行 SteamOS（Linux），强调开放性，允许用户自由修改软件。Valve 此前在 Steam Controller 上使用了类似的预约系统以防止倒卖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://store.steampowered.com/hardware/steammachine">Steam Machine</a></li>
<li><a href="https://www.4scarrsgaming.com/2026/05/valve-steam-machine-reservation-queue-scalper-protection.html">Valve Is Prepping a Steam Machine Reservation Queue to Block ...</a></li>
<li><a href="https://aftermath.site/steam-machine-review-price/">The Steam Machine Is An Iconoclastic Computer Born In Unforgiving...</a></li>

</ul>
</details>

**社区讨论**: 社区成员称赞公平的预约系统和开放硬件理念，一位用户强调了 Linux 支持的重要性。另一位指出真实的游戏片段与夸张的营销形成鲜明对比，令人耳目一新。

**标签**: `#gaming`, `#hardware`, `#Valve`, `#Steam Machine`, `#PC gaming`

---

<a id="item-2"></a>
## [近半数 LG 智能电视应用使用住宅代理 SDK](https://spur.us/blog/smart-tv-apps-residential-proxy-sdks) ⭐️ 8.0/10

Spur 扫描了 6038 个 LG 和三星智能电视应用，发现其中 2058 个（约 34%）包含住宅代理 SDK，这些 SDK 可在用户不知情的情况下将电视变成代理服务的出口节点。 这种做法带来严重的隐私风险，数百万智能电视可能被用作住宅代理网络的出口节点，可能暴露家庭网络流量，并助长网络爬虫或欺诈等不道德活动。 受影响的应用是第三方应用，而非 LG 内置应用，这些 SDK 通常隐藏在冗长的最终用户许可协议中，用户很少阅读。该研究聚焦于 LG 和三星应用，但问题可能扩展到其他智能电视平台。

hackernews · microcode · Jun 22, 20:48 · [社区讨论](https://news.ycombinator.com/item?id=48635954)

**背景**: 住宅代理 SDK 允许公司通过用户的家庭 IP 地址路由互联网流量，使其看起来像合法的住宅流量。这常用于网络爬虫、广告验证或绕过地理限制，但也可能被滥用于恶意目的。智能电视由于始终在线且连接到家庭网络，成为此类 SDK 的诱人目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://spur.us/blog/smart-tv-apps-residential-proxy-sdks">Nearly Half of LG Smart TV Apps Contain Residential Proxy SDKs</a></li>
<li><a href="https://gist.github.com/Firefishy/5e60867d2425a380cc0e28eebbbf3887">List of companies providing residential proxies or related SDKs</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了强烈的隐私担忧，许多人建议将智能电视隔离到单独的 VLAN 中，或使用不带智能功能的商用电视。有人指出问题仅限于第三方应用而非 LG 自带应用，并且 SDK 至少在 EULA 中有披露，尽管通常隐藏得很深。

**标签**: `#privacy`, `#smart TV`, `#security`, `#residential proxy`, `#LG`

---

<a id="item-3"></a>
## [Moebius：0.2B 参数修补模型声称达到 10B 级性能](https://hustvl.github.io/Moebius/) ⭐️ 8.0/10

研究人员发布了 Moebius，一个 0.2 亿参数的图像修补模型，声称其性能可与 100 亿参数模型媲美，社区还利用 ONNX 构建了浏览器演示。 这代表了 50 倍的参数效率提升，有望在消费级硬件和浏览器环境中实现高质量修补，使高级图像编辑更加普及。 该模型输出分辨率限制为 512x512，社区测试显示修补区域可能明显比周围更平滑，且对新颖物体表现不佳。

hackernews · DSemba · Jun 22, 13:53 · [社区讨论](https://news.ycombinator.com/item?id=48630171)

**背景**: 图像修补是填充图像中缺失或损坏部分的技术。大型基础模型（100 亿+参数）质量高但计算成本高昂。Moebius 旨在成为一个紧凑型专家模型，避免极端压缩带来的表示瓶颈。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/papers/2606.19195">Paper page - Moebius: 0.2B Lightweight Image Inpainting Framework with ...</a></li>
<li><a href="https://arxiv.org/abs/2606.19195">[2606.19195] Moebius: 0.2B Lightweight Image Inpainting Framework with ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/ONNX">ONNX</a></li>

</ul>
</details>

**社区讨论**: 社区成员构建了 ONNX 浏览器演示并测试了模型。虽然对其效率印象深刻，但也指出了局限性：修补区域更平滑、处理新颖物体能力差、分辨率限制为 512x512。有人对漫画翻译的专用版本表示兴趣。

**标签**: `#image inpainting`, `#efficient models`, `#computer vision`, `#deep learning`, `#ONNX`

---

<a id="item-4"></a>
## [Codex 日志漏洞可能向本地 SSD 写入 TB 级数据](https://github.com/openai/codex/issues/28224) ⭐️ 8.0/10

OpenAI 的 Codex CLI 中存在一个日志漏洞，导致 SQLite 反馈日志数据库每年向本地 SSD 写入约 640 TB 的数据，可能在数月内耗尽典型驱动器的寿命。修复程序已提交，预计将在下一个版本中发布。 该漏洞可能悄无声息地损坏或摧毁开发者的 SSD，导致硬件故障和数据丢失，尤其对频繁使用 Codex 的用户影响严重。这凸显了开发者工具中严格日志管理的重要性以及供应商及时响应的必要性。 该漏洞在 GitHub issue #28224 中跟踪，影响位于 ~/.codex/logs_2.sqlite 的 SQLite 数据库。社区提供的临时解决方法使用 SQLite 触发器阻止日志插入，而运行 VACUUM FULL 可将数据库从 27 GB 缩小到 73 MB。

hackernews · vantareed · Jun 22, 07:30 · [社区讨论](https://news.ycombinator.com/item?id=48626930)

**背景**: Codex 是 OpenAI 的 AI 编程助手，通过 CLI 在本地运行。它使用 SQLite 记录反馈日志，但一个配置错误的接收器导致过度写入。SSD 的寿命通常以总写入字节数（TBW）衡量；消费级 SSD 的 TBW 额定值通常为 150-600 TB，因此每年 640 TB 的写入量可能在一年内耗尽寿命。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/openai/codex/issues/28224">Codex logging bug may write TBs to local SSDs - GitHub</a></li>
<li><a href="https://www.reddit.com/r/OpenAI/comments/1ucf4px/openai_codex_has_a_bug_that_could_kill_your_ssd/">r/OpenAI on Reddit: OpenAI Codex has a bug that could kill your SSD in under a year</a></li>
<li><a href="https://www.techtimes.com/articles/318876/20260622/openai-codex-cli-bug-silently-writes-640-tb-year-your-ssd-no-patch.htm">OpenAI Codex CLI Bug Silently Writes 640 TB/Year to Your SSD ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 OpenAI 的缓慢响应表示不满，指出该漏洞已开放近六个月。一些用户分享了 SQLite 触发器和 VACUUM 等临时解决方法，而另一些用户则指出 Codex 是开源的，可以在本地进行修补。

**标签**: `#bug`, `#openai`, `#codex`, `#logging`, `#performance`

---

<a id="item-5"></a>
## [警察局长利用 Flock 车牌识别系统跟踪女性引发搜查令争议](https://ipvm.com/reports/police-chiefs-track) ⭐️ 8.0/10

一份报告揭露，警察局长利用 Flock Safety 的车牌识别系统跟踪女性，凸显了执法部门在获取此类监控数据前需要搜查令的紧迫性。 这种对监控技术的滥用威胁到公民自由和隐私，并凸显了警察不受限制地访问 Flock 车牌识别网络等大规模数据收集系统的更广泛风险。 Flock 摄像头拍摄所有过往车辆的车牌，并使用计算机视觉识别车辆；报告记录了具体的跟踪案例，包括一起涉及男性受害者的案件。

hackernews · jhonovich · Jun 22, 19:13 · [社区讨论](https://news.ycombinator.com/item?id=48634694)

**背景**: Flock Safety 是一家向警方和社区销售车牌识别摄像头的公司，声称这些设备有助于破案。然而，公民自由团体对隐私和潜在滥用表示担忧，因为这些系统收集所有车辆的数据，而不仅仅是嫌疑车辆。最近的立法努力试图要求对此类监控获得搜查令，但结果好坏参半。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.npr.org/2026/02/17/nx-s1-5612825/flock-contracts-canceled-immigration-survillance-concerns">Why some cities are canceling Flock license plate reader contracts : NPR</a></li>
<li><a href="https://stateofsurveillance.org/news/surveillance-accountability-act-massie-boebert-warrant-requirement-hr8470-2026/">Two Republicans Just Filed a Bill to Make the... - State of Surveillance</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了对滥用可能性的担忧，有人指出这与《黑衣人》中为个人目的使用监控的场景相似。其他人建议联系 ACLU，质疑此类摄像头违反第四修正案，少数人则讨论了破案与隐私之间的权衡。

**标签**: `#surveillance`, `#privacy`, `#law enforcement`, `#civil liberties`, `#technology abuse`

---

<a id="item-6"></a>
## [2025 年 Linux 安全启动证书到期](https://lwn.net/Articles/1029767/) ⭐️ 8.0/10

2011 年签发的 Linux 安全启动证书将于 2025 年到期，用户需要更新固件，否则可能面临启动失败。 这影响到许多依赖安全启动的 Linux 用户，如果不处理可能导致启动失败，并凸显了提供清晰、适合初学者的指南的必要性。 到期涉及微软 2011 年的 UEFI CA 证书，更新需要通过固件更新或使用 mokutil 等工具注册新证书。

hackernews · weaksauce · Jun 22, 18:24 · [社区讨论](https://news.ycombinator.com/item?id=48633941)

**背景**: 安全启动是一种 UEFI 功能，确保启动过程中只运行受信任的软件。用于签名引导加载程序的证书会定期到期，需要更新以维持信任。许多 Linux 发行版使用的微软 2011 年证书将在 2025-2026 年到期。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcommunity.microsoft.com/blog/windows-itpro-blog/secure-boot-playbook-for-certificates-expiring-in-2026/4469235">Secure Boot playbook for certificates expiring in 2026</a></li>
<li><a href="https://access.redhat.com/articles/7128933">Secure Boot Certificate Changes in 2026: Guidance for RHEL Environments - Red Hat Customer Portal</a></li>
<li><a href="https://support.microsoft.com/en-us/topic/secure-boot-certificate-updates-for-linux-on-azure-virtual-machines-df51ba85-4e1e-4eda-b1d8-f0881970e997">Secure Boot certificate updates for Linux on Azure virtual machines - Microsoft Support</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出缺乏适合初学者的指南，并提供了变通方法的链接，一些用户建议注册自定义密钥而不是依赖微软的证书。

**标签**: `#Linux`, `#Secure Boot`, `#security`, `#firmware`, `#system administration`

---

<a id="item-7"></a>
## [Mitchell Hashimoto 向 Zig 软件基金会承诺捐赠 40 万美元](https://mitchellh.com/writing/zig-donation-2026) ⭐️ 8.0/10

Ghostty 的创建者 Mitchell Hashimoto 宣布向 Zig 软件基金会承诺 2026 年捐赠 40 万美元，理由是 Zig 的潜力和社区价值观。 这笔巨额捐赠为 Zig 软件基金会提供了财务稳定性，支持了 Zig 作为一种有前途的系统编程语言的发展。它也凸显了围绕 Zig 不断增长的生态系统，包括像 Ghostty 这样的项目。 该承诺针对 2026 年，Hashimoto 强调 Zig 拥抱“怪异”的哲学及其反对 LLM 生成贡献的立场与他的价值观一致。用 Zig 编写的终端模拟器 Ghostty 已受到社区好评。

hackernews · tosh · Jun 22, 13:43 · [社区讨论](https://news.ycombinator.com/item?id=48630020)

**背景**: Zig 是一种通用系统编程语言，旨在改进 C 语言，具有编译时泛型和手动内存管理等功能。Zig 软件基金会 (ZSF) 通过捐赠和赞助来资助开发。Ghostty 是一个快速、跨平台的终端模拟器，使用 GPU 加速和原生 UI。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://ghostty.org/">Ghostty</a></li>
<li><a href="https://ziglang.org/">Home ⚡ Zig Programming Language</a></li>

</ul>
</details>

**社区讨论**: 评论者赞扬了 Hashimoto 的智慧以及 Zig 积极的社区价值观，一些人指出 Ghostty 的影响同样重大。其他人讨论了 Zig 反对 LLM 贡献的立场，并推荐了 Zig 创建者的采访给那些学习该语言的人。

**标签**: `#Zig`, `#donation`, `#systems programming`, `#open source`, `#Ghostty`

---

<a id="item-8"></a>
## [Claude Code 的扩展思考是带损摘要](https://patrickmccanna.net/the-text-in-claude-codes-extended-thinking-output-is-not-authentic/) ⭐️ 8.0/10

一篇博客文章揭示，Claude Code 的“扩展思考”输出并非模型的实际推理过程，而是一个有损摘要，引发了关于隐藏提示注入和数据泄露风险的担忧。 这很重要，因为隐藏推理削弱了 AI 系统的透明度和安全性，使得检测提示注入攻击更加困难，并可能让攻击者通过交错的函数调用窃取数据。 “扩展思考”功能生成一个有损摘要，类似于将无损 BMP 转换为有损 JPEG，而实际的推理链是加密的，对用户不透明。

hackernews · 0o_MrPatrick_o0 · Jun 22, 14:22 · [社区讨论](https://news.ycombinator.com/item?id=48630535)

**背景**: 扩展思考是 Claude Code 中的一个功能，显示模型思考过程的摘要。然而，实际的推理令牌是加密的，用户不可见。这种设计部分是为了保护专有推理技术不被竞争对手获取。提示注入攻击可以操纵 LLM 的推理，如果推理被隐藏，这类攻击就更难检测。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48630535">Claude Code's "extended thinking" is a summary- not authentic thinking | Hacker News</a></li>
<li><a href="https://support.claude.com/en/articles/10574485-using-extended-thinking">Change the model, effort, and thinking settings | Claude Help Center</a></li>
<li><a href="https://platform.claude.com/docs/en/build-with-claude/extended-thinking">Extended thinking - Claude API Docs</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，所有主要 AI 公司（OpenAI、Google、Anthropic）都隐藏推理以保护研发投入。有人认为这使得提示优化更加困难，并增加了安全风险，因为攻击者可以将恶意指令注入隐藏的推理链。其他人指出，有损摘要的类比有误（BMP 是无损的，JPEG 是有损的）。

**标签**: `#AI safety`, `#LLM reasoning`, `#transparency`, `#prompt injection`, `#Anthropic`

---

<a id="item-9"></a>
## [雪佛龙与微软签署 20 年天然气供电协议](https://www.chevron.com/newsroom/2026/q2/chevron-signs-20-year-power-agreement-with-microsoft-for-west-texas-data-center) ⭐️ 8.0/10

雪佛龙宣布与微软签署一项为期 20 年的购电协议，通过名为“Kilby 项目”的设施，为微软位于西得克萨斯的数据中心提供天然气发电。 该协议凸显了数据中心日益增长的能源需求，以及科技公司碳中和目标与化石燃料依赖之间的张力，尤其是在太阳能和电池储能等可再生能源成本不断下降的背景下。 该共址发电设施将使用卡特彼勒子公司 Solar Turbines 的天然气涡轮机，位于西得克萨斯靠近 Waha 枢纽的地区，该地区近期因供应过剩导致天然气价格为负值。

hackernews · cdrnsf · Jun 22, 13:43 · [社区讨论](https://news.ycombinator.com/item?id=48630029)

**背景**: 数据中心需要大量电力，而微软等科技公司已承诺到 2030 年实现碳负排放。然而，风能和太阳能等可再生能源具有间歇性，导致一些公司转向天然气以获取可靠的基荷电力。西得克萨斯的二叠纪盆地因石油开采产生大量伴生气，当供应超过管道输送能力时，天然气价格常出现负值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chevron.com/newsroom/2026/q2/chevron-signs-20-year-power-agreement-with-microsoft-for-west-texas-data-center">Chevron signs 20-year power agreement with Microsoft for West ...</a></li>
<li><a href="https://www.businesswire.com/news/home/20260622017964/en/Chevron-Signs-20-Year-Power-Agreement-with-Microsoft-for-West-Texas-Data-Center">Chevron Signs 20-Year Power Agreement with Microsoft for West ...</a></li>
<li><a href="https://www.cnbc.com/2026/06/22/chevron-cvx-microsoft-msft-natural-gas-data-center.html">Chevron to fuel massive Microsoft data center in Texas using ...</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，西得克萨斯天然气价格目前为负值，意味着生产商需付费才能将天然气运走，这使得该协议在经济上颇具吸引力。其他人则质疑微软的碳中和承诺，认为部署吉瓦级的新化石燃料容量与其 2030 年实现碳负排放的目标相矛盾。还有人指出，使用名为“Solar Turbines”的公司（实际生产燃气轮机）的涡轮机具有讽刺意味。

**标签**: `#energy`, `#data centers`, `#Microsoft`, `#natural gas`, `#sustainability`

---

<a id="item-10"></a>
## [PP-OCRv6 在 Hugging Face 发布，支持 50 种语言](https://huggingface.co/blog/PaddlePaddle/pp-ocrv6) ⭐️ 8.0/10

PaddlePaddle 推出的轻量级 OCR 系统 PP-OCRv6 已在 Hugging Face 上发布，支持 50 种语言，模型参数量从 1.5M 到 34.5M 不等。 此次发布通过 Hugging Face 使高质量的多语言 OCR 更易获取，无需大模型即可高效处理多种语言的文档。 PP-OCRv6 围绕统一的 MetaFormer 风格构建块重新设计了骨干网络、检测颈和识别颈，在 OCR 任务上性能超越了十亿参数级别的视觉语言模型。

rss · Hugging Face Blog · Jun 22, 13:18

**背景**: 光学字符识别（OCR）将文本图像转换为机器可读的文本。PaddleOCR 是 PaddlePaddle 开发的开源 OCR 工具包，支持多语言文本检测与识别。PP-OCRv6 是其最新版本，提供了多种模型大小以适应不同的部署场景。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.13108">[2606.13108] PP-OCRv6: From 1.5M to 34.5M Parameters, Surpassing Billion-Scale VLMs on OCR Tasks</a></li>
<li><a href="https://huggingface.co/collections/PaddlePaddle/pp-ocrv6">PP-OCRv6 - a PaddlePaddle Collection</a></li>
<li><a href="https://github.com/PaddlePaddle/PaddleOCR">GitHub - PaddlePaddle/PaddleOCR: Turn any PDF or image ...</a></li>

</ul>
</details>

**标签**: `#OCR`, `#multilingual`, `#deep learning`, `#Hugging Face`, `#PaddlePaddle`

---

<a id="item-11"></a>
## [OpenAI 推出 Daybreak 安全工具](https://openai.com/index/daybreak-securing-the-world) ⭐️ 8.0/10

OpenAI 宣布推出 Daybreak 工具套件，包括 Codex Security 和 GPT-5.5-Cyber，旨在大规模自动化漏洞发现、验证和修补。 这一举措将网络安全从被动修补转变为主动防御，可能改变组织防御威胁的方式。它利用 OpenAI 的前沿模型帮助防御者跟上不断加速的威胁形势。 Codex Security 于 2026 年 3 月 6 日发布研究预览版，逐次提交扫描 GitHub 仓库以检测和修补漏洞。GPT-5.5-Cyber 自 2026 年 5 月 7 日起在有限预览中，专为关键基础设施防御者定制，并在 AI 安全研究所评估中表现出色。

rss · OpenAI Blog · Jun 22, 10:00

**背景**: 传统的漏洞管理依赖人工和被动修补，往往使组织暴露在风险中。OpenAI 的 Daybreak 工具旨在利用 AI 代理和专用模型自动化整个生命周期——发现、验证和修复漏洞。Codex Security 构建项目特定的上下文和威胁模型，而 GPT-5.5-Cyber 是 OpenAI 最新模型的网络安全专用版本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/daybreak-securing-the-world/">Daybreak: Tools for securing every organization in the world</a></li>
<li><a href="https://openai.com/index/codex-security-now-in-research-preview/">Codex Security: now in research preview - OpenAI</a></li>
<li><a href="https://openai.com/index/gpt-5-5-with-trusted-access-for-cyber/">Scaling Trusted Access for Cyber with GPT-5.5 and GPT-5.5-Cyber | OpenAI</a></li>

</ul>
</details>

**标签**: `#AI Security`, `#Vulnerability Management`, `#OpenAI`, `#Cybersecurity`, `#Codex`

---

<a id="item-12"></a>
## [Oak：为 AI 代理打造的 Git 替代品](https://oak.space/oak/oak) ⭐️ 7.0/10

Oak 是一个为 AI 代理设计的早期版本控制系统，它通过虚拟挂载避免完整仓库拷贝，支持并行任务工作区而无需下载全部内容。 这解决了 AI 代理处理大型代码库时的 token 效率和上下文限制问题，可能降低成本并提升工作流并行性，但面临与现有 Git 生态兼容性的挑战。 Oak 仍处于早期开发阶段，没有 Windows 版本，缺少 CI、问题跟踪和评论等功能，但团队已自举使用数月，没有 Git 备份。

hackernews · zdgeier · Jun 22, 15:37 · [社区讨论](https://news.ycombinator.com/item?id=48631726)

**背景**: 像 Git 这样的版本控制系统可以跟踪代码随时间的变化，但 AI 代理通常需要克隆整个仓库，消耗 token 和存储。虚拟挂载允许代理按需访问文件，无需下载完整仓库，类似于 Google 的 google3 或 Microsoft 的 GVFS。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://oak.space/">Oak — Branch freely · oak</a></li>
<li><a href="https://github.com/darknight26/OAK-Version-Control-System">GitHub - darknight26/OAK-Version-Control-System</a></li>
<li><a href="https://github.com/open-gitagent/gitagent">GitHub - open-gitagent/gitagent: A universal git-native AI ...</a></li>

</ul>
</details>

**社区讨论**: 评论者担心模型训练偏向 Git，质疑是否有必要为节省 token 而创建新的 VCS。有人称赞懒加载挂载概念具有创新性，将其与 Google 内部系统比较，而另一些人则指出缺乏相对于 Git 的性能提升证据。

**标签**: `#version control`, `#AI agents`, `#developer tools`, `#git alternative`

---

<a id="item-13"></a>
## [加拿大计划 15 年内新建多达 10 座核反应堆](https://www.cbc.ca/news/politics/federal-nuclear-strategy-9.7244509) ⭐️ 7.0/10

加拿大宣布计划在未来 15 年内建造多达 10 座新核反应堆，利用其丰富的铀储量和成熟的 CANDU 反应堆技术。 这一扩张可能显著提升加拿大的清洁能源容量，支持油砂等工业部门的脱碳，并巩固其作为全球核技术领导者的地位。 该计划包括大型 CANDU 反应堆和小型模块化反应堆（SMR），其中 Darlington SMR 项目已在建设中。加拿大目前国内有 19 座运行中的 CANDU 反应堆，海外还有 9 座。

hackernews · geox · Jun 22, 19:06 · [社区讨论](https://news.ycombinator.com/item?id=48634585)

**背景**: CANDU（加拿大氘铀）是加拿大开发的加压重水反应堆设计，以使用天然铀为燃料并具有高安全性和效率而闻名。加拿大是世界上最大的铀生产国之一，在核反应堆建造和翻新方面拥有数十年经验，例如 Darlington 项目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CANDU_reactor">CANDU reactor - Wikipedia</a></li>
<li><a href="https://natural-resources.canada.ca/energy-sources/nuclear-energy-uranium/canadian-nuclear-energy-technology">The Canadian Nuclear Energy Technology - Natural Resources Canada</a></li>
<li><a href="https://www.atkinsrealis.com/en/projects/candu-technology">CANDU technology: helping Ontario achieve Net Zero</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍支持该计划，提到加拿大的铀储量、安全的 CANDU 设计以及需要基荷电力来补充可再生能源。一些人指出核能可用于油砂以减少二氧化碳排放，而另一些人则担心立法拖延。

**标签**: `#nuclear energy`, `#Canada`, `#energy policy`, `#CANDU`, `#clean energy`

---

<a id="item-14"></a>
## [GLM 5.2 与 Opus 对比：基准测试争议升温](https://techstackups.com/comparisons/glm-5.2-vs-opus/) ⭐️ 7.0/10

一项关于 GLM 5.2 与 Claude Opus 4 的对比引发争议，该对比使用单次提示测试，结果显示 GLM 5.2 落后于 Opus，尽管 GLM 5.2 在 Terminal-Bench 2.1 上取得了 81.0 的强劲基准分数。 这场辩论凸显了标准化基准测试与实际智能体性能之间的差距，影响着开发者为复杂编码任务选择模型的方式。 GLM 5.2 是一个开源模型，拥有 1M token 上下文和改进的推测解码，而 Claude Opus 4 是 Anthropic 的旗舰闭源模型。该对比使用单个单次提示在 WebGL 中构建一个 3D 平台游戏。

hackernews · ritzaco · Jun 22, 07:22 · [社区讨论](https://news.ycombinator.com/item?id=48626866)

**背景**: GLM 5.2 是智谱 AI 最新的开源模型，专为长周期任务设计，拥有 1M token 上下文。Claude Opus 4 是 Anthropic 最强大的模型，在编码和推理方面表现出色。单次提示测试评估模型从单个指令生成完整解决方案的能力，但批评者认为这不能反映现实世界中的协作使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openlm.ai/glm-5.2/">GLM-5.2 | OpenLM.ai</a></li>
<li><a href="https://github.com/zai-org/GLM-5">GitHub - zai-org/GLM-5: GLM-5: From Vibe Coding to Agentic ...</a></li>
<li><a href="https://www.anthropic.com/news/claude-4">Introducing Claude 4 \ Anthropic</a></li>

</ul>
</details>

**社区讨论**: 评论者批评单次提示方法不切实际，认为真正的智能体使用是协作性的，需要可靠性和可操控性。一些用户报告称，GLM 5.2 相比其他非前沿模型有显著提升，但仍不如 Opus，存在速度慢和规划时产生幻觉等问题。

**标签**: `#AI`, `#LLM`, `#benchmarking`, `#GLM`, `#Claude Opus`

---

<a id="item-15"></a>
## [Deno Desktop 支持多后端构建桌面应用](https://docs.deno.com/runtime/desktop/) ⭐️ 7.0/10

Deno Desktop 随 Deno v2.9.0（当前为 canary 版本）发布，允许使用 Deno 通过 CEF、Webview 或原始后端构建桌面应用，并计划引入共享运行时以减小二进制体积。 这扩展了 Deno 的应用场景，从服务端和 CLI 工具延伸到桌面应用开发，与 Electron 和 Tauri 竞争，并利用了 Deno 的安全性和 TypeScript 支持。 共享 CEF 运行时已在路线图中，可将每个应用的二进制体积降至几 MB，编译时授予的权限会嵌入到二进制文件中。

hackernews · GeneralMaximus · Jun 22, 05:38 · [社区讨论](https://news.ycombinator.com/item?id=48626137)

**背景**: Deno 是由 Node.js 创始人 Ryan Dahl 创建的安全 JavaScript/TypeScript 运行时。CEF（Chromium Embedded Framework）允许在应用中嵌入 Chromium 浏览器，而 Webview 则使用系统原生 Web 引擎。传统桌面应用开发需要捆绑浏览器引擎，导致二进制体积庞大。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.deno.com/runtime/desktop/">Desktop apps | Deno Docs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chromium_Embedded_Framework">Chromium Embedded Framework - Wikipedia</a></li>
<li><a href="https://github.com/chromiumembedded/cef">GitHub - chromiumembedded/cef: Chromium Embedded Framework (CEF). A simple framework for embedding Chromium-based browsers in other applications. · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区成员对共享运行时的 CEF 版本管理、与 Deno 权限系统的集成提出了担忧，并请求增加浏览器启动选项。总体情绪积极，用户对 Deno 的成熟度和新功能印象深刻。

**标签**: `#Deno`, `#Desktop`, `#CEF`, `#Webview`, `#Runtime`

---

<a id="item-16"></a>
## [sqlite-utils 4.0rc1 增加迁移和嵌套事务](https://simonwillison.net/2026/Jun/21/sqlite-utils-40rc1/#atom-everything) ⭐️ 7.0/10

sqlite-utils 4.0rc1 引入了内置的数据库迁移系统，并通过 db.atomic() 支持嵌套事务。 此版本通过提供轻量级、Python 风格的迁移框架简化了 SQLite 用户的模式管理，并通过嵌套事务实现了更安全的事务代码。 迁移定义为使用 @migrations() 装饰器装饰的 Python 函数，可通过 Python 或 CLI 应用。该系统不支持反向迁移，鼓励仅向前修复。

rss · Simon Willison · Jun 21, 23:35

**背景**: sqlite-utils 是一个 Python 库和 CLI 工具，提供对 SQLite 数据库的高级操作。迁移有助于随时间管理模式更改，而嵌套事务允许在更大事务内使用 SQLite 保存点进行原子操作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sqlite-utils.datasette.io/en/latest/migrations.html">Database migrations - sqlite - utils</a></li>
<li><a href="https://simonwillison.net/2026/Jun/21/sqlite-utils-40rc1/">sqlite - utils 4.0rc1 adds migrations and nested transactions</a></li>

</ul>
</details>

**标签**: `#Python`, `#SQLite`, `#database`, `#migrations`, `#open source`

---

<a id="item-17"></a>
## [OpenAI 推出 Patch the Planet 助力开源安全](https://openai.com/index/patch-the-planet) ⭐️ 7.0/10

OpenAI 推出了 Patch the Planet 计划，这是 Daybreak 项目的一部分，利用 AI 和专家审查帮助开源维护者发现、验证并修复广泛使用软件中的漏洞。 该计划旨在解决开源软件中的关键安全缺口，维护者往往缺乏修补漏洞的资源。通过结合 AI 与人类专家，它可能显著降低全球软件供应链中的被利用风险。 Patch the Planet 基于 OpenAI 的 Daybreak 网络安全计划，并与 Trail of Bits 和 HackerOne 合作。它将 AI 辅助的漏洞研究与人类专家审查相结合，以确保准确性和可靠性。

rss · OpenAI Blog · Jun 22, 10:00

**背景**: 开源软件被广泛使用，但通常由时间和资源有限的志愿者维护，使其成为攻击者的主要目标。OpenAI 的 Daybreak 计划专注于利用前沿 AI 模型帮助防御者大规模发现、验证和修补漏洞。Patch the Planet 将这一方法专门扩展到开源项目，旨在保护许多组织依赖的数字基础设施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/daybreak-securing-the-world/">Daybreak: Tools for securing every organization in the world</a></li>
<li><a href="https://www.wired.com/story/openai-launches-full-scale-effort-to-patch-open-source-bugs-as-it-takes-on-anthropics-mythos/">OpenAI Launches Full-Scale Effort to Patch Open-Source Bugs as It Takes on Anthropic’s Mythos | WIRED</a></li>

</ul>
</details>

**标签**: `#open-source`, `#security`, `#AI`, `#vulnerability`, `#OpenAI`

---

<a id="item-18"></a>
## [Codex 在长期项目中的技巧](https://openai.com/index/codex-maxxing-long-running-work) ⭐️ 6.0/10

Jason Liu 在 OpenAI 网站上发布了一篇博客文章，展示了如何使用 Codex 保持上下文并管理超出单次提示的复杂多步骤项目。 这很重要，因为它解决了 AI 编码助手的一个关键限制——在长时间会话中保持上下文——并为从事大型持续项目的开发者提供了实用策略。 这些技巧可能涉及上下文管理、压缩和迭代修复循环，如 OpenAI 的 Codex 文档中所述。该文章侧重于项目管理的实用提示工程。

rss · OpenAI Blog · Jun 22, 00:00

**背景**: Codex 是 OpenAI 的一个轻量级编码代理，可在本地计算机上运行。它可以通过 CLI 使用，或集成到 VS Code 等 IDE 中。AI 助手的一个常见挑战是在长时间运行的任务中丢失上下文，而本文旨在解决这一问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developers.openai.com/codex">Codex | OpenAI Developers</a></li>
<li><a href="https://github.com/openai/codex">GitHub - openai/ codex : Lightweight coding agent that runs in your...</a></li>

</ul>
</details>

**标签**: `#Codex`, `#AI-assisted development`, `#prompt engineering`, `#project management`

---

<a id="item-19"></a>
## [AI 周报#120：SpaceX 收购 Cursor、GLM 5.2 发布、Shazeer 跳槽 OpenAI](https://t.me/ai_newz/4625) ⭐️ 6.0/10

本周 AI 摘要报道了 SpaceX 以 600 亿美元收购 Cursor、智谱 AI 发布支持 100 万 token 上下文的 GLM 5.2、Noam Shazeer 离开谷歌加入 OpenAI，以及 Midjourney 宣布成立医学影像部门。 这些动态凸显了重要趋势：大型科技公司投资 AI 编程工具、开源模型推动长上下文边界、以及谷歌与 OpenAI 之间的人才争夺战愈演愈烈。 GLM 5.2 保留了 MIT 许可证和 API 定价，同时改进了架构以支持长上下文。Seedance 2.0 Mini 速度是 Fast 版本的两倍，价格便宜 30%。Shazeer 的跳槽距离谷歌斥资 27 亿美元收购 Character AI（主要目的是让他回归）不到两年。

telegram · ai_newz · Jun 22, 18:19

**背景**: Cursor 是一款 AI 驱动的代码编辑器，在开发者中广受欢迎。GLM 是中国 AI 公司智谱 AI 开发的一系列开源大语言模型。Noam Shazeer 是一位著名的 AI 研究员，曾共同领导谷歌的 Gemini 项目并创立了 Character AI。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.developer-tech.com/news/z-ai-glm-5-2-long-context-coding-agents/">What is GLM-5.2? Z.ai targets coding agentsWhat is GLM-5.2? Z ...</a></li>
<li><a href="https://github.com/zai-org/GLM-5">GitHub - zai-org/GLM-5: GLM-5: From Vibe Coding to Agentic ...</a></li>
<li><a href="https://www.businessinsider.com/google-veteran-founded-characterai-is-jumping-to-openai-talent-war-2026-6">A Google Veteran Who Founded Character.AI Is Jumping to ...</a></li>

</ul>
</details>

**标签**: `#LLM`, `#AI`, `#news`, `#SpaceX`, `#GLM`

---

