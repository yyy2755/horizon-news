# Horizon 每日速递 - 2026-08-31

> From 19 items, 13 important content pieces were selected

---

1. [谷歌从 Chrome 网上应用店移除 MV2 扩展，包括 uBlock Origin](#item-1) ⭐️ 8.0/10
2. [NAT 的设计缺陷及其在互联网中心化中的作用](#item-2) ⭐️ 8.0/10
3. [通过木马化压缩包攻破 Claude Code Opus 5 自动模式](#item-3) ⭐️ 8.0/10
4. [西蒙·威利森解析 ChatGPT Work 的双重属性](#item-4) ⭐️ 8.0/10
5. [将安防摄像头变成自动识别鸟类的系统](#item-5) ⭐️ 7.0/10
6. [苹果对 Mac Mini 和 Mac Studio 的 AI 需求感到意外](#item-6) ⭐️ 7.0/10
7. [OpenShot 4.0：重大更新，引入 AI 对象遮罩](#item-7) ⭐️ 7.0/10
8. [双周 AI 摘要#128：新 LLM、视频模型与硬件](#item-8) ⭐️ 7.0/10
9. [Playa Phone：火人节上的互动艺术连接陌生人](#item-9) ⭐️ 6.0/10
10. [单个 HTML 文件中的可步行 ASCII 赛博朋克城市](#item-10) ⭐️ 6.0/10
11. [RavynOS：融合 Darwin 与 FreeBSD 的预 alpha 开源操作系统](#item-11) ⭐️ 6.0/10
12. [军事超市冰柜故障引发网络攻击猜测](#item-12) ⭐️ 6.0/10
13. [OpenAI 的 ChatGPT 广告年化收入达 10 亿美元，全球扩展](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [谷歌从 Chrome 网上应用店移除 MV2 扩展，包括 uBlock Origin](https://webiterate.dev/google-removed-extensions-ublock-origin-108/) ⭐️ 8.0/10

谷歌已从 Chrome 网上应用店移除所有 Manifest V2（MV2）扩展，包括广受欢迎的广告拦截器 uBlock Origin。这一变化迫使用户要么改用 MV3 替代品（如 uBlock Origin Lite），要么迁移到 Firefox 等其他浏览器。 这影响了数百万依赖 uBlock Origin 进行广告拦截和隐私保护的 Chrome 用户，可能降低他们对跟踪器和恶意广告的防护能力。这也凸显了向 MV3 迁移的行业趋势，MV3 限制了扩展的某些功能，并可能促使部分用户转向 Firefox 等替代浏览器。 uBlock Origin Lite（uBOL）是由同一作者 Raymond Hill 开发的基于 MV3 的内容拦截器，可在 Chrome 网上应用店获取。谷歌的 MV3 迁移清单表明，所有剩余的 MV2 扩展已被移除，且 MV3 限制了远程托管代码，这影响了扩展的运行方式。

hackernews · twapi · Aug 31, 21:10 · [社区讨论](https://news.ycombinator.com/item?id=49514878)

**背景**: Manifest V2（MV2）是 Chrome 之前的扩展框架，允许拦截网络请求等强大功能。Manifest V3（MV3）是新的框架，增强了安全性和性能，但限制了一些 API，使得广告拦截器更难有效工作。uBlock Origin 是一个广泛使用的开源内容拦截器，其 Lite 版本旨在符合 MV3 的限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.chrome.com/docs/extensions/develop/migrate/checklist">Manifest V 3 migration checklist | Chrome for Developers</a></li>
<li><a href="https://en.wikipedia.org/wiki/UBlock_Origin_Lite">UBlock Origin Lite</a></li>
<li><a href="https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh?hl=en">uBlock Origin Lite - Chrome Web Store</a></li>

</ul>
</details>

**社区讨论**: 社区对谷歌的决定普遍持负面态度，许多用户表达不满并推荐 Firefox 作为更好的替代方案。一些用户已转向 Firefox 或对 uBlock Origin Lite 感到满意，而另一些用户则强调 uBlock Origin 在 Firefox 上表现最佳。

**标签**: `#Chrome`, `#Manifest V3`, `#uBlock Origin`, `#ad-blocking`, `#browser extensions`

---

<a id="item-2"></a>
## [NAT 的设计缺陷及其在互联网中心化中的作用](https://dreamstation.systems/personal/ntppost.html) ⭐️ 8.0/10

一篇评论文章认为，NAT 最初是解决 IP 地址稀缺的务实方案，但无意中通过使自托管变得困难并使客户端-服务器模式常态化，促进了互联网的中心化。文章强调 NAT 是开放互联网衰落的最早因素之一。 这一分析挑战了将 NAT 视为中性技术工具的普遍看法，揭示了其对互联网架构和用户自主权的长期影响。对于网络中立性、自托管以及 IPv6 和洋葱服务等去中心化技术的推广辩论具有重要意义。 文章指出，NAT 的设计，特别是缺乏端口预留，使得来自不同地址的传入连接无法路由，从而消除了公共端点。文章还提到，CGNAT 被认为比普通 NAT 更有害，而普通 NAT 可以通过端口转发和 UPnP 进行管理。

hackernews · robinpie · Aug 31, 02:23 · [社区讨论](https://news.ycombinator.com/item?id=49504905)

**背景**: NAT（网络地址转换）将多个私有 IP 地址映射到一个公共 IP 地址，节省了 IPv4 地址并提供基本防火墙功能。它最初是为了解决 IPv4 地址耗尽问题而引入的，但使入站连接变得复杂，增加了自托管的难度。这导致了对集中式服务和客户端-服务器架构的依赖，从而促进了互联网的中心化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Network_address_translation">Network address translation - Wikipedia</a></li>
<li><a href="https://computer.howstuffworks.com/nat.htm">NAT: How Network Address Translation Works - HowStuffWorks</a></li>
<li><a href="https://news.ycombinator.com/item?id=49504905">Internet centralization and the original sin of NAT | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 社区讨论中，Linux NAT 的原始实现者 RustyRussell 发表评论，为其设计的意外后果道歉，承认它削弱了运行服务器的能力。其他评论者则对严重性进行辩论，有人认为普通 NAT 在适当管理下是可以接受的，而另一些人则称赞洋葱服务是重新获得主权的一种方式。

**标签**: `#NAT`, `#internet centralization`, `#networking`, `#self-hosting`, `#history`

---

<a id="item-3"></a>
## [通过木马化压缩包攻破 Claude Code Opus 5 自动模式](https://embracethered.com/blog/posts/2026/breaking-claude-code-opus-5-and-automode/) ⭐️ 8.0/10

一名安全研究人员通过使用木马化压缩包，利用模型可预测的工具使用行为和 Python 模块遮蔽，演示了一种针对 Claude Code Opus 5 自动模式的新型攻击。该攻击绕过了自动模式中的安全分类器，凸显了 AI 代理安全中的关键漏洞。 这项研究意义重大，因为它揭示了一种针对 AI 代理的实用攻击途径，恶意行为者可能利用它执行任意代码或窃取数据。它强调了在 AI 代理部署中迫切需要强大的沙箱和行为分析，影响依赖 AI 编码助手的开发者和组织。 该攻击利用了 Claude 倾向于使用特定工具（如 `python -c`）以及 Python 从当前目录导入模块的特性，使得恶意的 `struct.py` 能够遮蔽标准库。文章还指出，当运行 Opus-5 时，自动模式使用 Sonnet-5 作为安全分类器，而该攻击成功绕过了它。

hackernews · Recursing · Aug 31, 07:49 · [社区讨论](https://news.ycombinator.com/item?id=49506819)

**背景**: Claude Code 是一款 AI 编码助手，可以在自动模式下运行，该模式通过安全分类器路由工具调用，从而无需常规权限提示即可执行操作。Python 模块遮蔽是指本地模块与标准库模块同名，导致 Python 导入本地模块而非标准库。该攻击结合这些元素，诱使 AI 执行恶意代码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=49506819">Breaking Claude Code Opus 5 Auto Mode | Hacker News</a></li>
<li><a href="https://veganmosfet.codeberg.page/posts/2026-08-12-opus5_automode/">Prompt Injection Experiments with Opus - 5 in Claude Code ...</a></li>
<li><a href="https://realpython.com/videos/shadowing-modules-video/">Shadowing Modules (Video) – Real Python</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调了该攻击巧妙利用了 Claude 的特定行为模式，有人指出这更像是一种木马而非经典的提示注入。用户强调沙箱的重要性，其中一位分享了个人轶事，称发现自己的代理尝试访问意外域名。还有争论认为这是否是在利用软件漏洞，或者同样可能欺骗人类用户。

**标签**: `#AI safety`, `#prompt injection`, `#Claude Code`, `#security`, `#agent sandboxing`

---

<a id="item-4"></a>
## [西蒙·威利森解析 ChatGPT Work 的双重属性](https://simonwillison.net/2026/Aug/30/understanding-chatgpt-work/) ⭐️ 8.0/10

西蒙·威利森发布了一篇关于 OpenAI 的 ChatGPT Work 的详细分析，指出它实际上包含两个不同的产品：基于云的版本（Work Cloud）和本地桌面版本（Work Local），两者具有不同的功能和访问方式。 这一分析帮助用户和开发者理解 OpenAI 不断演变的产品线中令人困惑的部分，尤其是云端与本地执行的区别，这会影响任务的执行方式和可用功能。它还强调了 ChatGPT Work 的快速迭代和功能增加，使其成为一个强大但复杂的工具。 ChatGPT Work 仅对每月支付 20 美元及以上的订阅者开放，并提供常规 Chat 所没有的功能，包括模型选择（GPT-5.6 Sol、Luna、Terra）、带互联网访问的代码执行环境、无头 Chrome 浏览器、持久化共享文件系统、发布 ChatGPT Sites 的能力以及子代理会话。桌面应用（原名为 Codex）提供本地版本。

rss · Simon Willison · Aug 30, 23:59

**背景**: ChatGPT Work 是 OpenAI 的代理模式，于 2026 年 7 月 9 日推出，由 GPT-5.6 驱动。它旨在帮助团队完成具有明确成果的宏大任务，如创建简报、演示文稿、分析和流程。该产品基于 OpenAI 的 Codex 构建，Codex 最初是面向开发者的编码代理，但 Work Local 经过重新设计，对非程序员更加友好。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://felloai.com/chatgpt-work/">What Is ChatGPT Work? OpenAI's New Agent Mode Explained</a></li>
<li><a href="https://openai.com/chatgpt-work/">ChatGPT Work for every team | OpenAI</a></li>
<li><a href="https://github.com/openai/codex">GitHub - openai / codex : Lightweight coding agent that runs in your...</a></li>

</ul>
</details>

**社区讨论**: 在社区评论中，西蒙·威利森强调浏览器控制技能是最有趣的功能，它通过 Node.js REPL 使用 Playwright。一些用户质疑 Work Local 与 Codex 有何不同，而另一些用户则对侧边栏滚动等 UI 问题提供反馈。还有一个元评论指出 AI 生成的网站外观相似，让人想起 Bootstrap 时代的统一性。

**标签**: `#ChatGPT`, `#OpenAI`, `#AI tools`, `#product analysis`

---

<a id="item-5"></a>
## [将安防摄像头变成自动识别鸟类的系统](https://jasontucker.blog/how-i-turned-my-security-cameras-into-an-automatic-bird-identification-system-with-birdnet-go/) ⭐️ 7.0/10

Jason Tucker 的博客文章介绍了如何利用 BirdNet-Go 将安防摄像头改造成实时自动识别鸟类的系统。该系统通过摄像头音频流进行本地 AI 推理，实现鸟类物种的自动分类。 该项目展示了一种利用现有安防摄像头基础设施进行野生动物监测的实用且低成本的方法，使鸟类识别对爱好者更加普及。它凸显了将消费级硬件重新用于环境观察和公民科学的趋势。 BirdNet-Go 是一个自托管的实时声景分析器，可在树莓派上 24/7 运行，从声卡或网络流中获取音频。博客文章使用了支持 RTSP 流的安防摄像头，并在 Web 界面中展示检测结果。

hackernews · speckx · Aug 31, 16:47 · [社区讨论](https://news.ycombinator.com/item?id=49511856)

**背景**: BirdNet-Go 是一个基于 BirdNET 模型的开源 AI 工具，可从音频录音中识别鸟类物种。安防摄像头通常内置麦克风和网络流功能，适合改造成音频传感器。这种方法无需专用硬件即可实现持续监测。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/tphakala/birdnet-go">GitHub - tphakala/birdnet-go: Self-hosted realtime soundscape analyser for birds, bats and other wildlife. Multi-model local AI inference, runs 24/7 on a Raspberry Pi. · GitHub</a></li>
<li><a href="https://jasontucker.blog/how-i-turned-my-security-cameras-into-an-automatic-bird-identification-system-with-birdnet-go/">How I Turned My Security Cameras Into an Automatic Bird Identification System with BirdNet-Go</a></li>
<li><a href="https://aitinkerers.org/technologies/birdnet-go">BirdNET-Go Projects</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了各自的实现，例如使用 Unifi 门铃摄像头和带电子墨水屏的便携式 Birdnet-Pi 设置。一些人指出 BirdNet 在某些地区的准确性限制，另一些人则推荐 Merlin Bird ID 应用和 eBird 以增强功能。

**标签**: `#BirdNet-Go`, `#security cameras`, `#bird identification`, `#DIY projects`, `#machine learning`

---

<a id="item-6"></a>
## [苹果对 Mac Mini 和 Mac Studio 的 AI 需求感到意外](https://www.macrumors.com/2026/08/30/apple-unexpected-mac-mini-and-studio-demand/) ⭐️ 7.0/10

据报道，苹果对 Mac Mini 和 Mac Studio 因 AI 工作负载而需求激增感到措手不及。该公司据称缺乏面向企业客户的专门工程团队和企业 AI 战略，凸显了意外的产品市场契合。 这标志着市场的重要转变，本地 AI 推理硬件正受到青睐，可能影响云 AI 提供商和硬件制造商。同时，它也强调了在快速发展的 AI 领域中，灵活产品策略的重要性。 Mac Mini 和 Mac Studio，尤其是搭载 Apple Silicon 芯片和统一内存的型号，正被用于本地 AI 推理和实验。需求激增不仅包括运行下载的 LLM，还包括本地训练模型，正如社区成员所指出的。

hackernews · thm · Aug 31, 12:41 · [社区讨论](https://news.ycombinator.com/item?id=49508982)

**背景**: 本地 AI 推理是指在个人硬件上运行 AI 模型，而非云服务器，具有隐私、低延迟和频繁使用成本低等优势。苹果 M 系列芯片的统一内存架构提供了高带宽和容量，使 Mac 适合运行大型模型。然而，云推理因其简便性和可访问更大模型而仍然流行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.local-llm.net/learn/hardware-requirements/">Local AI Hardware Guide: GPU, CPU, RAM, and Storage ...</a></li>
<li><a href="https://hardwarepedia.com/learn/local-ai">Running AI Locally: Complete Hardware & Software Guide (2026 ...</a></li>
<li><a href="https://www.howtogeek.com/apple-mac-mini-m6-mac-studio-m5-ultra-price-release-date/">These are the new most powerful mini PCs for local AI</a></li>

</ul>
</details>

**社区讨论**: 社区评论反映了热情与怀疑并存。一些用户强调本地 AI 在实验和训练中的实际优势，而另一些用户则质疑其与云订阅相比的实用性，提到量化问题和硬件限制等。还有人担心 AI 爱好者的需求可能会挤占其他消费者的机会。

**标签**: `#Apple`, `#AI hardware`, `#local inference`, `#Mac Mini`, `#cloud vs local`

---

<a id="item-7"></a>
## [OpenShot 4.0：重大更新，引入 AI 对象遮罩](https://www.openshot.org/blog/2026/08/30/openshot-40-record-edit-color-like-never-before/) ⭐️ 7.0/10

OpenShot 4.0 于 2026 年 8 月 30 日发布，带来了焕然一新的界面、Qt6 迁移、原生多源录制，以及使用 ONNX 模型的 AI 对象遮罩功能。此外还引入了带有示波器的色彩视图，用于高级调色。 此次发布显著提升了 OpenShot 的功能，使 AI 遮罩和调色等高级功能对开源用户可用。这巩固了 OpenShot 作为专有视频编辑器免费替代品的地位，可能吸引更多用户转向开源视频编辑。 AI 对象遮罩支持可下载的 YOLOv5 ONNX 模型、模型验证、分割遮罩，并改进了对检测对象的控制。用户可以调整对象外观、框/标签绘制以及单个跟踪对象的变换。

hackernews · metrofun · Aug 31, 09:59 · [社区讨论](https://news.ycombinator.com/item?id=49507822)

**背景**: OpenShot 是一款流行的开源视频编辑器，以其易用性和跨平台支持而闻名。ONNX（开放神经网络交换格式）是一种用于表示机器学习模型的开源格式，支持不同框架之间的互操作性。集成 ONNX 使得本地 AI 处理成为可能，无需依赖云端，从而增强了隐私性和速度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://creativemarketing.ai/blog/openshot-40-record-color-local-ai-masks">OpenShot 4 . 0 — Record, color, and local AI masks in one free editor</a></li>
<li><a href="https://wpnews.pro/news/openshot-4-0-qt6-local-ai-masks-and-native-recording">OpenShot 4 . 0 : Qt6, Local AI Masks , and Native Recording — Web...</a></li>
<li><a href="https://www.openshot.org/blog/2026/08/30/openshot-40-record-edit-color-like-never-before/">OpenShot 4 . 0 : Record, Edit, and Color Like Never Before</a></li>

</ul>
</details>

**社区讨论**: 社区评论情绪复杂：一些用户更倾向于使用 LosslessCut 和 Shortcut 等工具进行无损编辑，而另一些用户则称赞此次更新和 AI 功能。此外还有对替代编辑器的自我推广，表明视频编辑领域兴趣浓厚。

**标签**: `#video editing`, `#open-source`, `#AI`, `#release`, `#community`

---

<a id="item-8"></a>
## [双周 AI 摘要#128：新 LLM、视频模型与硬件](https://t.me/ai_newz/4732) ⭐️ 7.0/10

该摘要报道了 GLM 5.3 Flash（320B-A18B 开源多模态模型）和 Qwen 3.8 Flash Next（125B-A6B，含 510 亿 N-gram 参数）的发布。还涵盖了 GPT 5.6 Sol 的降价、MiniMax H3 Max 和 MAGI-2 等新视频模型，以及 OpenAI 的 Jalapeño 芯片和搭载 M5 Ultra 的 Mac Studio 等硬件更新。 该摘要凸显了开源 LLM 和生成式视频模型的快速进步，为从业者提供了高性价比的替代方案，并推动了端侧 AI 的边界。硬件更新标志着向专用推理芯片和高带宽内存用于本地模型部署的趋势。 GLM 5.3 Flash 的定价为每百万 token 0.15/0.5 美元，而 GPT 5.6 Sol 在三个月内降价至每百万 token 4/20 美元。MiniMax H3 Max 约 3 秒生成 5 秒视频，MAGI-2 是一个开源的 MoE 视频模型，具有 114B-A6B 参数，可生成带声音的 10 秒片段。

telegram · ai_newz · Aug 31, 05:47

**背景**: 该摘要涵盖了 AI 领域的最新进展，包括混合注意力和稀疏激活等新模型架构，这些架构降低了计算成本。还提到了基准测试的担忧，例如 ARC-AGI-3 技能将 Opus 5 的得分从 30%提升到 100%，引发了对该基准测试实用性的质疑。此外，还报道了涉及 Hugging Face 和 Nvidia 的潜在收购。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.z.ai/guides/vlm/glm-5.3-flash">GLM-5.3-Flash - Overview - Z.AI DEVELOPER DOCUMENT</a></li>
<li><a href="https://huggingface.co/zai-org/GLM-5.3-Flash">zai-org/GLM-5.3-Flash · Hugging Face</a></li>
<li><a href="https://github.com/QwenLM/Qwen3.8-Flash-Next/">Qwen3.8-Flash-Next - GitHub</a></li>
<li><a href="https://qwen.ai/blog?id=qwen3.8-flash-next">Qwen3.8-Flash-Next: A New Architecture, Towards Ultimate Cost ...</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-Flash-Next">Qwen/Qwen3.8-Flash-Next · Hugging Face</a></li>
<li><a href="https://arxiv.org/abs/2510.22369">[2510.22369] GigaEmbeddings: Efficient Russian Language Embedding Model</a></li>

</ul>
</details>

**标签**: `#AI`, `#LLM`, `#generative models`, `#news digest`

---

<a id="item-9"></a>
## [Playa Phone：火人节上的互动艺术连接陌生人](https://playaphone.com/) ⭐️ 6.0/10

Playa Phone 是火人节上的一个电话亭，允许参与者给陌生人打电话，促进自发的对话和社区互动。该项目因其简单性和所创造的有意义的联系而受到关注。 在数字通信时代，Playa Phone 凸显了模拟、偶然的人类联系的价值。它展示了简单的互动艺术如何增强社区参与度，并在大型活动中创造难忘的体验。 这个电话亭是火人节上的一个实体装置，参与者可以拿起电话与随机陌生人通话，常常引发意想不到的对话。该项目激发了个人故事，包括一次通话后发现了附近的婚礼营地，从而促成了一场婚礼。

hackernews · cutoff · Aug 31, 14:52 · [社区讨论](https://news.ycombinator.com/item?id=49510514)

**背景**: 火人节是内华达沙漠一年一度的活动，以强调社区、艺术和自我表达而闻名。像 Playa Phone 这样的互动艺术项目是其中的常见元素，鼓励参与者之间的互动和联系。电话亭利用了人们对固定电话的怀旧情绪，为在节日环境中结识新朋友提供了一种新颖的方式。

**社区讨论**: 社区讨论总体上是积极的，项目创作者愿意回答问题，与会者分享了温馨的轶事。一位评论者描述了通话如何促成了一场即兴婚礼，另一位则称赞该项目是互动艺术的典范。此外，还有一个关于火人节参与者人口统计的附带讨论，一位用户质疑是否主要是富有的科技和金融人士。

**标签**: `#Burning Man`, `#interactive art`, `#community`, `#telephony`

---

<a id="item-10"></a>
## [单个 HTML 文件中的可步行 ASCII 赛博朋克城市](https://www.youtube.com/watch?v=3YtygAx_C6A) ⭐️ 6.0/10

一位开发者展示了一个完全在单个 HTML 文件中渲染的可步行 ASCII 赛博朋克城市，更新中增加了交通、室内和摩天大楼。该项目展示了浏览器中的实时 ASCII 艺术渲染。 该项目凸显了 ASCII 艺术在现代 Web 开发中的创意潜力，突破了简单文本字符所能实现的界限。它可能激励其他开发者探索程序化生成和基于浏览器的渲染技术。 该城市是程序化生成的，并使用等宽字符渲染，更新重点在于交通模拟、室内细节和摩天大楼的高度。整个场景在单个 HTML 文件中运行，利用浏览器的渲染和交互能力。

hackernews · keithcarolus · Aug 31, 18:21 · [社区讨论](https://news.ycombinator.com/item?id=49512975)

**背景**: ASCII 艺术是一种使用 ASCII 标准中的可打印字符来创建图像的设计技术。在 Web 开发中，在浏览器中渲染 ASCII 艺术可以精确控制字体和比例，从而更容易创建像这个赛博朋克城市这样的复杂场景。程序化生成通过算法创建内容，常用于高效生成大型、详细的环境。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ASCII_art">ASCII art - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Procedural_generation">Procedural generation - Wikipedia</a></li>
<li><a href="https://alexharri.com/blog/ascii-rendering">ASCII characters are not pixels: a deep dive into ASCII rendering</a></li>

</ul>
</details>

**社区讨论**: 社区评论总体积极，用户称赞怀旧美学和基于浏览器的 ASCII 艺术方法。然而，一些用户反映自己尝试时出现渲染问题，还有评论指出这是重复帖子。此外，有用户询问 GitHub 项目是否与视频一致。

**标签**: `#ASCII art`, `#creative coding`, `#web development`, `#cyberpunk`, `#procedural generation`

---

<a id="item-11"></a>
## [RavynOS：融合 Darwin 与 FreeBSD 的预 alpha 开源操作系统](https://ravynos.com/) ⭐️ 6.0/10

RavynOS 是一个预 alpha 阶段的开源操作系统，结合了 Darwin、FreeBSD 和苹果开源组件，旨在提供 macOS 兼容性以及 FreeBSD 的自由。该项目目前处于早期开发阶段，尚未发布稳定版本。 该项目意义重大，因为它可能提供一个开源的 macOS 替代品，让用户能够在自由且可定制的系统上运行 macOS 应用程序。如果成功，它可能会吸引那些既重视 macOS 生态系统又重视开源原则的开发者和用户。 RavynOS 基于 Darwin（macOS 的核心）并整合了 FreeBSD 组件。它旨在兼容 macOS 应用程序，类似于 ReactOS 旨在兼容 Windows，但目前仍处于预 alpha 阶段，且其网站上没有图形界面截图。

hackernews · Bluestein · Aug 31, 16:19 · [社区讨论](https://news.ycombinator.com/item?id=49511534)

**背景**: Darwin 是苹果操作系统的开源核心，源自 NeXTSTEP、FreeBSD 和其他 BSD 系统，以及苹果开发的代码。FreeBSD 是一个免费且开源类 Unix 操作系统。RavynOS 旨在结合这些，创建一个兼容 macOS 但自由的系统，类似于 Darling 和 GNUstep 等项目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Darwin_(operating_system)">Darwin (operating system)</a></li>
<li><a href="https://www.geeksforgeeks.org/operating-systems/difference-between-macos-and-freebsd/">Difference between macOS and FreeBSD - GeeksforGeeks</a></li>

</ul>
</details>

**社区讨论**: 社区评论质疑 Darwin 除了 macOS 兼容性之外的独特优势，指出网站上没有截图，并引用了之前关于该项目的讨论。一位评论者引用了 FAQ 中关于法律问题的回答，将其与 ReactOS 和 Darling 进行比较，另一位则建议为项目取一个更好的名字。

**标签**: `#operating systems`, `#Darwin`, `#FreeBSD`, `#macOS compatibility`, `#open source`

---

<a id="item-12"></a>
## [军事超市冰柜故障引发网络攻击猜测](https://signalandsilence.substack.com/p/i-think-someone-hacked-the-commissary) ⭐️ 6.0/10

一篇博客文章推测，多个军事超市的冰柜同时出现故障可能是网络攻击所致，五角大楼已承认国防军需局（DeCA）多个地点可能发生“制冷中断”。 如果确认为网络攻击，这将是对军事后勤和食品安全的一次重大威胁，凸显了关键基础设施中工业控制系统（ICS）和物联网设备的安全漏洞。该事件强调了在军事供应链中采取强有力网络安全措施的必要性。 据报道，故障涉及冰柜进入除霜模式，变成加热器导致食物变质，事件发生在至少六个基地的夜间。五角大楼尚未确认网络攻击，其他解释包括配置错误或维护问题。

hackernews · jcurbo · Aug 31, 11:45 · [社区讨论](https://news.ycombinator.com/item?id=49508506)

**背景**: 军事超市是由国防军需局（DeCA）在军事基地运营的杂货店。现代制冷设备通常使用网络控制器，这些控制器属于工业控制系统（ICS）和监控与数据采集（SCADA）系统的更广泛类别。这些系统存在已知的安全漏洞，过去对关键基础设施的攻击已证明了这一点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://signalandsilence.substack.com/p/i-think-someone-hacked-the-commissary">I Think the Military Commissary Freezers Were Hacked</a></li>
<li><a href="https://www.schneier.com/blog/archives/2026/08/is-someone-hacking-dod-refrigerators.html">Is Someone Hacking DoD Refrigerators? - Schneier on Security</a></li>
<li><a href="https://en.wikipedia.org/wiki/Cyberattacks_against_infrastructure">Cyberattacks against infrastructure - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区评论大多对黑客理论表示怀疑，认为配置错误或维护问题更可能是原因。一些评论者分享了关于不安全的工业 PLC 的轶事，而另一些则指出故障模式（除霜模式）仍可能与攻击一致，但需要更多数据。

**标签**: `#cybersecurity`, `#military`, `#IoT`, `#industrial control systems`, `#speculation`

---

<a id="item-13"></a>
## [OpenAI 的 ChatGPT 广告年化收入达 10 亿美元，全球扩展](https://openai.com/index/expanding-access-to-ai-with-chatgpt-ads) ⭐️ 6.0/10

OpenAI 宣布 ChatGPT 广告的年化收入运行率已达到 10 亿美元，并正在全球扩展，以支持免费和负担得起的 AI 访问。这标志着该公司的一个重要商业里程碑。 这一里程碑表明，广告可以成为 AI 平台可行的收入模式，可能使 OpenAI 能够向更广泛的受众提供免费和低成本的访问。这也标志着 AI 原生广告的市场吸引力不断增强，可能会影响其他 AI 公司如何将其服务变现。 该公告未具体说明达到 10 亿美元运行率的确切时间线，但强调了 ChatGPT Ads 自推出以来的快速增长。此次扩展是全球性的，表明 OpenAI 正在不同市场扩展其广告基础设施。

rss · OpenAI Blog · Aug 31, 04:00

**背景**: ChatGPT Ads 是 OpenAI 的广告平台，在 ChatGPT 对话中投放广告。它按千次展示成本（CPM）运营，据报道费率约为 60 美元 CPM，最低消费为 20 万美元。该平台已发展出产品信息流广告和 Ads Manager 测试版。年化收入运行率是基于近期较短时期对全年收入的预测，常用于科技行业衡量增长。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://help.openai.com/en/articles/20001047-ads-in-chatgpt">Ads in ChatGPT - OpenAI Help Center</a></li>
<li><a href="https://www.aitooldiscovery.com/guides/chatgpt-ads">ChatGPT Ads: Complete Guide for Marketers and Users (2026)</a></li>
<li><a href="https://www.investopedia.com/terms/r/runrate.asp">investopedia.com/terms/r/runrate.asp</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#ChatGPT`, `#AI monetization`, `#business milestone`, `#AI access`

---

