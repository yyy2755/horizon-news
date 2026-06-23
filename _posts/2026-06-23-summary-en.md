---
layout: default
title: "Horizon Summary: 2026-06-23 (EN)"
date: 2026-06-23
lang: en
---

> From 36 items, 27 important content pieces were selected

---

1. [Apple Acquires Swift Package Index](#item-1) ⭐️ 8.0/10
2. [TikZ Editor: WYSIWYG for LaTeX Figures](#item-2) ⭐️ 8.0/10
3. [AI's Affordability Crisis: Unsustainable Model Costs](#item-3) ⭐️ 8.0/10
4. [Unlimited OCR: One-Shot Long-Horizon Parsing](#item-4) ⭐️ 8.0/10
5. [AI Hiring Tools Create Algorithmic Monocultures](#item-5) ⭐️ 8.0/10
6. [Armin Ronacher on the Human Bottleneck in AI Coding Agents](#item-6) ⭐️ 8.0/10
7. [Google Fires Employee for Creating Workspace CLI](#item-7) ⭐️ 8.0/10
8. [Lift4D: Single-View 4D Reconstruction In-the-Wild](#item-8) ⭐️ 8.0/10
9. [Anthropic Launches Claude Tag, a Multi-User AI Agent for Slack](#item-9) ⭐️ 8.0/10
10. [Prompt Injection as Role Confusion](#item-10) ⭐️ 8.0/10
11. [Porting Moebius 0.2B Inpainting Model to Browser with WebGPU](#item-11) ⭐️ 8.0/10
12. [GPT-5 Helps Solve 3-Year Immunology Mystery](#item-12) ⭐️ 8.0/10
13. [IO-Aware GNN Layers Achieve 8.5x Speedup and 76x Memory Reduction](#item-13) ⭐️ 8.0/10
14. [ByteDance Announces SeeDance 2.5 with Native 4K and IP Platform](#item-14) ⭐️ 8.0/10
15. [Don't verify email addresses by sending spam to them](#item-15) ⭐️ 7.0/10
16. [FUTO Releases New Swipe Typing Model for Privacy Keyboard](#item-16) ⭐️ 7.0/10
17. [Vitamin D Benefits Real but Often Exaggerated](#item-17) ⭐️ 7.0/10
18. [F3: A New Columnar Storage Format with Embedded WASM Decoders](#item-18) ⭐️ 7.0/10
19. [Digital Euro Gains EU Parliamentary Backing](#item-19) ⭐️ 7.0/10
20. [IBM's CUGA: Lightweight Harness for Agentic Apps with 24 Examples](#item-20) ⭐️ 7.0/10
21. [Hugging Face's AI-Assisted Weekly Release Pipeline](#item-21) ⭐️ 7.0/10
22. [Hugging Face Tests Cross-Origin Storage API for Browser ML](#item-22) ⭐️ 7.0/10
23. [OpenAI Joins Appia Foundation for AI Standards](#item-23) ⭐️ 7.0/10
24. [Jerry's Map: Hand-Drawn Imaginary Land Since 1963](#item-24) ⭐️ 6.0/10
25. [Germany Train Halt Due to Radio System Outage](#item-25) ⭐️ 6.0/10
26. [Mistral Launches OCR 4 Amid Benchmark Skepticism](#item-26) ⭐️ 6.0/10
27. [OPFS + Pyodide Test Harness for Datasette Lite](#item-27) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Apple Acquires Swift Package Index](https://swiftpackageindex.com/blog/swift-package-index-joins-apple) ⭐️ 8.0/10

Apple has acquired the Swift Package Index (SPI), a community-run resource for discovering Swift packages. The SPI team will join Apple to work on improving the Swift package ecosystem. This acquisition signals Apple's strategic investment in the Swift ecosystem and could lead to tighter integration of package discovery within Apple's developer tools. However, it raises concerns about the future openness and governance of the index under Apple's stewardship. The Swift Package Index currently indexes metadata from over 11,000 packages. Apple explicitly mentioned developer identity as a future direction, which has sparked community concern about potential restrictions.

hackernews · JDevlieghere · Jun 23, 18:00 · [Discussion](https://news.ycombinator.com/item?id=48648779)

**Background**: The Swift Package Index is a community-maintained website that helps developers discover Swift packages by indexing metadata from GitHub repositories. It complements the Swift Package Manager (SPM), Apple's official tool for managing Swift package dependencies. The acquisition follows Apple's pattern of absorbing community tools to improve its developer ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://swiftpackageindex.com/">Swift Package Index</a></li>
<li><a href="https://github.com/swiftlang/swift-package-manager">GitHub - swiftlang/swift-package-manager: The Package Manager for the Swift Programming Language · GitHub</a></li>
<li><a href="https://developer.apple.com/documentation/xcode/swift-packages">Swift packages | Apple Developer Documentation</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed: some are happy for the SPI team, while others worry about Apple's track record with open source and developer services. Concerns include potential regulation of which packages get indexed and the emphasis on developer identity as a future direction.

**Tags**: `#Swift`, `#Apple`, `#Package Management`, `#Open Source`, `#Developer Tools`

---

<a id="item-2"></a>
## [TikZ Editor: WYSIWYG for LaTeX Figures](https://tikz.dev/editor/) ⭐️ 8.0/10

An open-source WYSIWYG editor for TikZ figures has been released, allowing users to visually drag and resize elements while the source code and rendered output stay in sync. The editor was built almost entirely using the Codex coding agent. This tool addresses a major pain point for academics and LaTeX users who manually tweak coordinates and recompile to create figures, potentially saving significant time. It also demonstrates how coding agents can enable software that was previously too tedious to build manually. The editor parses TikZ code and tracks the exact source location of each object, so dragging an element only overrides the coordinate numbers without altering other code structure. It also includes converters from SVG, PPTX, and IPE to TikZ, and reimplements LaTeX hyphenation and line-breaking for multi-line nodes.

hackernews · DominikPeters · Jun 23, 14:24 · [Discussion](https://news.ycombinator.com/item?id=48645437)

**Background**: TikZ is a powerful LaTeX package for creating vector graphics programmatically, commonly used in academic papers. Traditionally, users write code with commands like \draw and \node, then recompile to see the result, making iterative adjustments tedious. WYSIWYG editors allow direct manipulation of the visual output, but existing tools for TikZ lacked synchronized source-code editing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/PGF/TikZ">PGF/TikZ - Wikipedia</a></li>
<li><a href="https://www.overleaf.com/learn/latex/TikZ_package">TikZ package - Overleaf, Online LaTeX Editor</a></li>
<li><a href="https://en.wikipedia.org/wiki/WYSIWYG_editor">WYSIWYG editor</a></li>

</ul>
</details>

**Discussion**: The community praised the project's UI and concept, but some users criticized the generated TikZ code for using absolute coordinates unnecessarily, suggesting that relative positioning would be more idiomatic. Others compared it to specialized tools like quiver.app and noted the potential of coding agents in building such complex software.

**Tags**: `#LaTeX`, `#TikZ`, `#editor`, `#academic`, `#open-source`

---

<a id="item-3"></a>
## [AI's Affordability Crisis: Unsustainable Model Costs](https://blog.dshr.org/2026/06/ais-affordability-crisis.html) ⭐️ 8.0/10

A blog post argues that AI model development and serving costs are unsustainably high, creating an affordability crisis for enterprises. This debate highlights a critical tension in the AI industry: while model capabilities advance rapidly, the economic viability for widespread enterprise adoption remains uncertain, potentially slowing investment and innovation. Commenters note that token-based pricing has led to rapid changes in enterprise usage patterns, with companies now monitoring and restricting use of expensive models. Some argue the real issue is poor ROI, not high costs.

hackernews · ilreb · Jun 23, 15:11 · [Discussion](https://news.ycombinator.com/item?id=48646276)

**Background**: AI models like those from OpenAI and Anthropic require massive compute resources for training and inference, leading to high costs. Enterprises have been adopting AI aggressively, but the return on investment is not always clear.

**Discussion**: Commenters are divided: some see an affordability crisis due to high costs, while others argue it's a financial crisis driven by poor ROI. There is debate over whether companies like OpenAI and Anthropic are subsidizing enterprise customers, and whether Chinese or open models will drive prices down.

**Tags**: `#AI`, `#economics`, `#cost`, `#enterprise`, `#debate`

---

<a id="item-4"></a>
## [Unlimited OCR: One-Shot Long-Horizon Parsing](https://github.com/baidu/Unlimited-OCR) ⭐️ 8.0/10

Baidu released Unlimited OCR, a 3B-parameter model that uses a novel architectural hack called R-SWA to prevent memory hoarding in the KV cache, enabling one-shot parsing of entire books without VRAM crashes. This innovation eliminates the need to chunk long documents into pages, significantly simplifying OCR workflows and reducing memory costs, which is critical as AI memory shortages persist. The model is released under the MIT license, supports both 'gundam' and 'base' inference configs, and surpasses the DeepSeek OCR baseline in long-horizon parsing.

hackernews · ingve · Jun 23, 11:35 · [Discussion](https://news.ycombinator.com/item?id=48643426)

**Background**: OCR (Optical Character Recognition) converts images of text into machine-readable text. Traditional AI-based OCR for long documents suffers from VRAM crashes because the KV cache grows linearly with input length. Developers often resort to chunking documents page by page, which is inefficient and loses context.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/baidu/Unlimited-OCR">GitHub - baidu/Unlimited-OCR: Unlimited OCR Works: Welcome the Era of One-shot Long-horizon Parsing. · GitHub</a></li>
<li><a href="https://arxiv.org/html/2606.23050v1">Unlimited OCR Works Welcome the Era of One-shot Long-horizon Parsing</a></li>
<li><a href="https://aiweekly.co/alerts/baidu-releases-mit-licensed-3b-ocr-model-for-long-documents">Baidu Releases MIT-Licensed 3B OCR Model for Long Documents | AI Weekly</a></li>

</ul>
</details>

**Discussion**: The community praised the clever architectural hack and the MIT license, with some noting the name is a reference to Fate/stay night. Users also discussed applications in music recognition and local RAG systems.

**Tags**: `#OCR`, `#AI`, `#memory optimization`, `#deep learning`, `#open source`

---

<a id="item-5"></a>
## [AI Hiring Tools Create Algorithmic Monocultures](https://hai.stanford.edu/news/ai-hiring-tools-can-yield-racial-bias-and-systemic-rejection) ⭐️ 8.0/10

Stanford research reveals that AI hiring tools can create algorithmic monocultures, leading to systemic rejection and racial bias across multiple job applications. This matters because as a single hiring vendor dominates an industry, candidates may be completely locked out, amplifying biases and reducing fairness in hiring. The study found that 10% of applicants who submit four applications are rejected from all positions when screened by the same algorithmic vendor, a pattern not seen with independent decisions.

hackernews · sizzle · Jun 23, 18:56 · [Discussion](https://news.ycombinator.com/item?id=48649673)

**Background**: Algorithmic monoculture occurs when the same algorithm or algorithms made with similar data dominate a sector, leading to uniform decisions. In hiring, AI tools are increasingly used to screen resumes, but they can inherit biases from training data, potentially disadvantaging minority groups.

<details><summary>References</summary>
<ul>
<li><a href="https://digitaleconomy.stanford.edu/news/qa-algorithmic-monoculture/">Q&A | Algorithmic Monoculture in Hiring - Stanford Digital Economy Lab</a></li>
<li><a href="https://mitsloan.mit.edu/ideas-made-to-matter/ai-reinventing-hiring-same-old-biases-heres-how-to-avoid-trap">AI is reinventing hiring — with the same old biases. Here’s how to avoid that trap | MIT Sloan</a></li>
<li><a href="https://en.wikipedia.org/wiki/Monoculture_(computer_science)">Monoculture (computer science) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the finding of systemic rejection is intuitive—rejected resumes are likely to be rejected everywhere. Some questioned the methodology for determining race and whether the algorithm is blind to race, suggesting candidate discrepancies could explain results.

**Tags**: `#AI ethics`, `#algorithmic bias`, `#hiring`, `#fairness`, `#research`

---

<a id="item-6"></a>
## [Armin Ronacher on the Human Bottleneck in AI Coding Agents](https://lucumr.pocoo.org/2026/6/23/the-coming-loop/) ⭐️ 8.0/10

Armin Ronacher argues that AI coding agents are most effective when given clear, well-specified goals, but the human bottleneck of writing specifications remains, and the 'loop' of iterative prompting often masks a lack of understanding. This analysis highlights a critical limitation of current AI coding tools: they amplify human clarity but cannot replace it, meaning the quality of output depends heavily on the user's ability to specify requirements precisely. Ronacher notes that the iterative 'loop' of prompting can give an illusion of progress while actually hiding a lack of deep understanding, and that writing good specs is a significant cognitive load on the developer.

hackernews · ingve · Jun 23, 11:06 · [Discussion](https://news.ycombinator.com/item?id=48643180)

**Background**: AI coding agents, such as Claude Code, use large language models to generate code based on natural language prompts. Specification-driven development is a methodology where a detailed specification is written before coding, serving as a source of truth for both humans and AI.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Armin_Ronacher">Armin Ronacher - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Specification-driven_development">Specification-driven development</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree with Ronacher's assessment, sharing experiences that writing clear specs is the main bottleneck. Some note that the iterative loop is unavoidable for gaining understanding, and that AI can help interrogate requirements but not replace human thinking.

**Tags**: `#AI coding agents`, `#software engineering`, `#LLM limitations`, `#specification-driven development`

---

<a id="item-7"></a>
## [Google Fires Employee for Creating Workspace CLI](https://twitter.com/JPoehnelt/status/2069482265953087602) ⭐️ 8.0/10

Justin Poehnelt, a Google employee, was fired for releasing a Google Workspace CLI tool that could be mistaken for an official product. The tool was built on personal time but used Google branding, leading to termination. This incident highlights the tension between employee innovation and corporate bureaucracy, especially at a company like Google that once encouraged 20% time projects. It raises questions about how companies handle side projects that gain popularity but violate internal policies. The CLI tool was released under the name 'googleworkspace/cli' on GitHub, which could easily be confused with an official Google product. Poehnelt likely did not go through Google's internal release approval process (IARC or ossreleasing), as noted in community comments.

hackernews · justinwp · Jun 23, 18:13 · [Discussion](https://news.ycombinator.com/item?id=48649011)

**Background**: Google has a history of encouraging side projects through '20% time,' but also enforces strict policies on releasing code that could be seen as official. The Google Workspace CLI is a real, officially released tool (as of March 2026), but Poehnelt's version was not sanctioned. This case echoes previous firings at Google for policy violations, such as the 2024 protests over the Israel cloud contract.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/googleworkspace/cli">GitHub - googleworkspace/cli: Google Workspace CLI — one command-line tool for Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin, and more. Dynamically built from Google Discovery Service. Includes AI agent skills.</a></li>
<li><a href="https://www.infoq.com/news/2026/06/google-workspace-cli/">Google Workspace CLI: Unified Command-Line Tool Built for Humans and AI Agents - InfoQ</a></li>

</ul>
</details>

**Discussion**: Community comments are divided: some criticize Poehnelt for poor judgment in releasing something that could be confused with an official product, while others sympathize, citing Pournelle's Iron Law of Bureaucracy and lamenting Google's shift away from encouraging innovation. A few note that termination seems harsh but predictable given the circumstances.

**Tags**: `#Google`, `#CLI`, `#employment`, `#bureaucracy`, `#open source`

---

<a id="item-8"></a>
## [Lift4D: Single-View 4D Reconstruction In-the-Wild](https://lift4d.github.io/) ⭐️ 8.0/10

Lift4D introduces a method for harmonizing single-view 3D estimation to achieve 4D reconstruction from monocular video, enabling full scene and object tracking without requiring human subjects. This work advances 4D reconstruction from single-view video, which is crucial for applications like augmented reality, robotics, and forensics, by handling severe occlusions and non-rigid motion in real-world scenes. Lift4D uses an occlusion-aware optimization with a view-conditioned diffusion prior to recover visible surface details and complete unobserved regions, improving over prior methods on challenging in-the-wild sequences.

hackernews · ilreb · Jun 23, 14:40 · [Discussion](https://news.ycombinator.com/item?id=48645721)

**Background**: 4D reconstruction aims to recover dynamic 3D scenes over time from video. Single-view methods are particularly challenging due to limited information and occlusions. Lift4D addresses this by harmonizing per-frame 3D estimates into a consistent 4D representation.

<details><summary>References</summary>
<ul>
<li><a href="https://lift4d.github.io/">Lift4D: Harmonizing Single-View 3D Estimation for 4D Reconstruction In-the-Wild</a></li>

</ul>
</details>

**Discussion**: Commenters expressed excitement about the method, with some drawing parallels to sci-fi concepts and questioning its accuracy for forensic use. Others requested code release and comparisons to related work like SAM-Body4D.

**Tags**: `#4D reconstruction`, `#computer vision`, `#single-view 3D`, `#neural rendering`, `#3D estimation`

---

<a id="item-9"></a>
## [Anthropic Launches Claude Tag, a Multi-User AI Agent for Slack](https://www.anthropic.com/news/introducing-claude-tag) ⭐️ 8.0/10

Anthropic has launched Claude Tag, an always-on AI agent that lives in Slack and can be summoned by any channel member to collaborate on tasks. It is available in beta for Claude Enterprise and Team customers. Claude Tag represents a significant step toward agentic platforms, enabling multi-user, persistent collaboration with AI in a workplace communication tool. This could transform enterprise productivity by treating AI as a true teammate. Claude Tag is multiplayer: within a Slack channel, there is one Claude that interacts with everyone, allowing anyone to see its work and continue conversations. Anthropic claims 65% of their product team's code is created by an internal version of Claude Tag.

hackernews · adocomplete · Jun 23, 17:09 · [Discussion](https://news.ycombinator.com/item?id=48648039)

**Background**: AI agents are autonomous systems that can perform tasks, make decisions, and interact with users. Claude Tag extends this concept by embedding an AI agent directly into Slack, a popular enterprise messaging platform, allowing it to participate in ongoing conversations and handle tasks collaboratively.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/23/anthropics-claude-tag-is-learning-your-company-one-slack-message-at-a-time/">Anthropic’s Claude Tag is learning your company, one Slack message at a time | TechCrunch</a></li>
<li><a href="https://www.anthropic.com/news/introducing-claude-tag">Introducing Claude Tag \ Anthropic</a></li>
<li><a href="https://fortune.com/2026/06/23/anthropic-claude-tag-virtual-employee-tool-slack/">Anthropic releases Claude Tag, a virtual employee that works within Slack | Fortune</a></li>

</ul>
</details>

**Discussion**: Community comments highlight concerns about token costs, as Claude Tag may parse every message in a channel, and enterprise security and permission alignment. Some see it as a step toward treating AI agents as employees with liability, while others note the potential for workforce reduction.

**Tags**: `#AI agents`, `#Slack`, `#Anthropic`, `#enterprise AI`, `#productivity`

---

<a id="item-10"></a>
## [Prompt Injection as Role Confusion](https://simonwillison.net/2026/Jun/22/prompt-injection-as-role-confusion/#atom-everything) ⭐️ 8.0/10

A new paper titled 'Prompt Injection as Role Confusion' reveals that LLMs cannot reliably distinguish privileged text from user input, and that models prioritize the style of text over its actual content, enabling novel jailbreaks. This research confirms a fundamental limitation in LLM security, showing that current defenses against prompt injection are fundamentally flawed and may require a paradigm shift in how models perceive roles. The researchers found that 'destyling' text—rewriting it to look less like the expected format in a role tag—reduced attack success rates from 61% to 10%, even though the meaning remained unchanged to human readers.

rss · Simon Willison · Jun 22, 23:59

**Background**: Prompt injection is a cybersecurity exploit where malicious inputs cause LLMs to behave unintentionally, bypassing safeguards. Jailbreaking refers to attempts to bypass safety constraints in LLMs. This paper introduces 'role confusion' as the underlying mechanism, where models mistake user input for their own privileged instructions based on stylistic similarity.

<details><summary>References</summary>
<ul>
<li><a href="https://role-confusion.github.io/">Prompt Injection as Role Confusion</a></li>
<li><a href="https://arxiv.org/html/2603.12277v2">Prompt Injection as Role Confusion</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection</a></li>

</ul>
</details>

**Tags**: `#prompt injection`, `#LLM security`, `#AI safety`, `#jailbreak`, `#role confusion`

---

<a id="item-11"></a>
## [Porting Moebius 0.2B Inpainting Model to Browser with WebGPU](https://simonwillison.net/2026/Jun/22/porting-moebius/#atom-everything) ⭐️ 8.0/10

Simon Willison successfully ported the Moebius 0.2B image inpainting model to run in the browser using WebGPU, and released a live demo at simonw.github.io/moebius-web/. The port was accomplished with the help of Claude Code, using ONNX Runtime Web on the WebGPU backend. This demonstrates that lightweight yet powerful AI models can run entirely in the browser without requiring dedicated GPU hardware, making advanced image inpainting accessible to a wider audience. It also showcases the feasibility of using AI coding agents like Claude Code to accelerate model porting tasks. The original Moebius model required PyTorch and NVIDIA CUDA, but Willison used ONNX Runtime Web with the WebGPU backend to run it in the browser. The model has 0.2B parameters and claims performance comparable to 10B+ models like FLUX.1-Fill-Dev, with over 15x inference acceleration.

rss · Simon Willison · Jun 22, 23:43

**Background**: Image inpainting is a technique where missing or unwanted parts of an image are filled in plausibly by an AI model. Moebius is a lightweight inpainting framework that achieves high quality with only 0.2B parameters. WebGPU is a modern web standard that allows web applications to access the GPU for accelerated computation, enabling complex AI models to run in the browser efficiently.

<details><summary>References</summary>
<ul>
<li><a href="https://hustvl.github.io/Moebius/">Moebius Project Page</a></li>
<li><a href="https://simonwillison.net/2026/Jun/22/porting-moebius/">Porting the Moebius 0.2B image inpainting model to run in the browser with Claude Code</a></li>
<li><a href="https://github.com/hustvl/Moebius">GitHub - hustvl/Moebius: [ECCV 2026] Moebius: 0.2B Lightweight Image Inpainting Framework with 10B-Level Performance · GitHub</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (thread ID 48630171) showed strong interest, with many users impressed by the in-browser performance and the use of Claude Code for porting. Some commenters discussed the trade-offs between model size and quality, and the potential for more models to be ported to WebGPU.

**Tags**: `#image inpainting`, `#WebGPU`, `#browser AI`, `#model porting`, `#machine learning`

---

<a id="item-12"></a>
## [GPT-5 Helps Solve 3-Year Immunology Mystery](https://openai.com/index/gpt-5-immunology-mystery) ⭐️ 8.0/10

OpenAI's GPT-5 Pro model assisted immunologist Derya Unutmaz in solving a three-year-old mystery about T cell behavior, providing new insights into how T cells function. This breakthrough was announced by OpenAI and highlights a concrete application of GPT-5 in scientific research. This demonstrates that large language models like GPT-5 can accelerate biomedical discovery by analyzing complex data and generating hypotheses, potentially leading to advances in cancer and autoimmune disease treatments. It also showcases AI's growing role as a research partner in scientific fields. The specific mystery involved T cell behavior, which is central to immune responses. GPT-5 Pro was used to analyze data and propose mechanisms that had eluded researchers for three years. The results are expected to inform future research on cancer immunotherapy and autoimmune disorders.

rss · OpenAI Blog · Jun 23, 17:00

**Background**: T cells are a type of white blood cell that play a key role in the immune system by recognizing and attacking infected or cancerous cells. They are activated when their T cell receptor binds to an antigen presented by an MHC complex on antigen-presenting cells. Understanding T cell behavior is crucial for developing treatments for cancer and autoimmune diseases, where T cells may be overactive or underactive.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/T_cell">T cell - Wikipedia</a></li>
<li><a href="https://www.immunology.org/public-information/bitesized-immunology/systems-processes/t-cell-activation">T-cell activation | British Society for Immunology</a></li>

</ul>
</details>

**Tags**: `#GPT-5`, `#immunology`, `#AI in science`, `#cancer research`, `#autoimmune disease`

---

<a id="item-13"></a>
## [IO-Aware GNN Layers Achieve 8.5x Speedup and 76x Memory Reduction](https://research.yandex.com/blog/on-efficient-scaling-of-gnns-via-io-aware-layer-implementations) ⭐️ 8.0/10

Researchers from Yandex introduced IO-aware layer implementations for Graph Neural Networks (GNNs), achieving up to 8.5x speedup and 76x memory reduction by optimizing data movement between memory and compute units. The work was published as a spotlight paper at ICML. This work addresses a critical bottleneck in GNN training on GPUs, similar to how FlashAttention revolutionized transformer efficiency. The drop-in replacement implementations can significantly accelerate GNN workloads in production and research. For attention layers, the approach uses IO-aware techniques akin to FlashAttention; for aggregation layers, it adds extra parallelization for vertices with many neighbors. The authors also found that for some convolutional layers, NVIDIA's existing solutions are already faster than most specialized implementations.

telegram · ai_newz · Jun 23, 12:04

**Background**: Graph Neural Networks (GNNs) process graph-structured data by aggregating information from neighboring nodes. The core operation, neighbor aggregation, involves irregular memory access patterns that are inefficient on modern GPUs optimized for ordered reads like matrix multiplication. FlashAttention is a prior IO-aware algorithm that dramatically improved transformer efficiency by reducing data movement between GPU high-bandwidth memory (HBM) and on-chip SRAM.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/FlashAttention">FlashAttention</a></li>
<li><a href="https://proceedings.neurips.cc/paper_files/paper/2022/file/67d57c32e20fd0a7a302cb81d36e40d5-Supplemental-Conference.pdf">FLASHATTENTION: Fast and Memory-Efﬁcient Exact Attention with IO-Awareness</a></li>

</ul>
</details>

**Tags**: `#Graph Neural Networks`, `#GPU Optimization`, `#IO-Aware`, `#Efficient Scaling`, `#ICML`

---

<a id="item-14"></a>
## [ByteDance Announces SeeDance 2.5 with Native 4K and IP Platform](https://t.me/ai_newz/4627) ⭐️ 8.0/10

ByteDance announced SeeDance 2.5 at the Volcengine FORCE conference, adding support for up to 50 multimodal references including 3D models, prompt-based editing, and native 4K output. Additionally, they launched a commercial IP licensing platform and updated Seedream 5.0 Pro with layer editing and Seed-Audio 1.0. This update significantly advances AI video generation by enabling native 4K resolution and multimodal control, which could transform content creation workflows. The IP licensing platform also addresses copyright concerns, potentially setting a new standard for legal AI-generated content commercialization. SeeDance 2.5 supports up to 50 multimodal references including 3D models, and native 4K is also being added to the existing SeeDance 2.0. The IP platform's first partner is Hong Kong director Stephen Chow, with daily generation volumes exceeding 100,000 for his comedies. SeeDance 2.5 is scheduled for release in July.

telegram · ai_newz · Jun 23, 14:06

**Background**: SeeDance is ByteDance's AI video generation model, competing with tools like Sora and Runway. Native 4K means the model outputs video at 3840x2160 resolution without upscaling, offering higher quality. Multimodal references allow users to input images, 3D models, or other media to guide generation. The IP platform lets copyright holders license content for AI remixing, with revenue shared between parties.

<details><summary>References</summary>
<ul>
<li><a href="https://wavespeed.ai/blog/posts/seedream-4-0-to-5-0-complete-tutorial-image-generation-editing/">Seedream 4.0 to 5.0 Complete Tutorial: Text-to-Image, Editing, and Multi-Image Generation | WaveSpeed Blog</a></li>
<li><a href="https://www.rundiffusion.com/seedream-5-0">Seedream 5.0 Guide: Real-Time Web Search, Controllable Editing, and Logical AI Image Generation | RunDiffusion</a></li>
<li><a href="https://seed.bytedance.com/en/seedream4_5">Seedream 4.5</a></li>

</ul>
</details>

**Tags**: `#AI video generation`, `#ByteDance`, `#4K`, `#IP licensing`, `#multimodal`

---

<a id="item-15"></a>
## [Don't verify email addresses by sending spam to them](https://milek7.pl/mailverifyspam/) ⭐️ 7.0/10

A blog post warns that some services may send spam to verify email addresses, sparking debate about verification methods and privacy risks. This practice could violate user trust and privacy, as users may receive unsolicited emails simply for signing up. It highlights the need for better email verification standards. The author received spam-like emails after signing up for a service, and the base64-encoded email contained filler text about magnetic domains. Some commenters suggest the spam might be coincidental or due to a leak.

hackernews · garaetjjte · Jun 23, 20:23 · [Discussion](https://news.ycombinator.com/item?id=48650837)

**Background**: Email verification typically involves sending a one-time link or code to confirm ownership. However, some services may use third-party verification tools that could inadvertently send marketing or spam emails, raising privacy concerns.

**Discussion**: Commenters are divided: some believe the spam is coincidental, while others suspect malicious practices. One user noted the email contained unusual filler text, suggesting automated generation.

**Tags**: `#security`, `#privacy`, `#email`, `#verification`, `#spam`

---

<a id="item-16"></a>
## [FUTO Releases New Swipe Typing Model for Privacy Keyboard](https://swipe.futo.tech/) ⭐️ 7.0/10

FUTO has released a new swipe typing model for its privacy-respecting Android keyboard, achieving near-Gboard quality with fully local processing. This update significantly improves the swipe typing experience on a privacy-focused keyboard, making it a viable alternative to mainstream keyboards like Gboard without sacrificing user privacy. The new model runs entirely offline and never connects to the internet, ensuring all typing data stays on the device. Users have reported that the swipe accuracy now rivals Gboard, though some minor issues like random capitalization and lack of context-aware suggestions remain.

hackernews · futohq · Jun 23, 17:50 · [Discussion](https://news.ycombinator.com/item?id=48648619)

**Background**: Swipe typing allows users to input words by sliding their finger from letter to letter without lifting, relying on algorithms and language models to predict the intended word. FUTO Keyboard is a fully offline, privacy-focused keyboard for Android that previously had poor swipe performance, which this update aims to fix.

<details><summary>References</summary>
<ul>
<li><a href="https://keyboard.futo.org/">FUTO Keyboard</a></li>
<li><a href="https://play.google.com/store/apps/details?id=org.futo.inputmethod.latin.playstore&hl=en_US">FUTO Keyboard - Apps on Google Play</a></li>

</ul>
</details>

**Discussion**: Community feedback is overwhelmingly positive, with users praising the new swipe model as a game-changer that finally makes FUTO Keyboard a daily driver. Some users note minor issues like "whats" instead of "what's" and random capitalization, but overall sentiment is that it's close enough to Gboard to switch permanently.

**Tags**: `#keyboard`, `#privacy`, `#machine learning`, `#open source`, `#mobile`

---

<a id="item-17"></a>
## [Vitamin D Benefits Real but Often Exaggerated](https://dynomight.net/vitamin-d/) ⭐️ 7.0/10

A detailed critique argues that vitamin D supplementation provides real benefits, especially for those severely deficient, but the hype often exaggerates its effects, with many studies flawed by poor methodology. This balanced analysis helps clarify the ongoing debate about vitamin D, potentially influencing public health recommendations and reducing unnecessary supplementation among those with adequate levels. The article highlights that the strongest evidence for vitamin D is in severely deficient individuals, and that many studies fail to measure baseline levels or account for factors like vitamin K2 co-supplementation.

hackernews · surprisetalk · Jun 23, 16:30 · [Discussion](https://news.ycombinator.com/item?id=48647486)

**Background**: Vitamin D is essential for bone health and immune function, but optimal levels and supplementation benefits are debated. Many observational studies show associations with various health outcomes, but large randomized trials often fail to confirm benefits, leading to skepticism.

**Discussion**: Commenters generally praised the balanced analysis, with some noting that health influencers often pivot to claiming widespread deficiency to explain away negative study results. Others raised points about the importance of measuring blood levels and co-factors like vitamin K2.

**Tags**: `#nutrition`, `#vitamin D`, `#evidence-based medicine`, `#health research`

---

<a id="item-18"></a>
## [F3: A New Columnar Storage Format with Embedded WASM Decoders](https://github.com/future-file-format/f3) ⭐️ 7.0/10

F3 is a new open-source columnar storage format that embeds WebAssembly (Wasm) decoders directly into each file, enabling universal compatibility without requiring native decoders. It aims to address limitations of Parquet by allowing easy addition of new encoding schemes. F3 could disrupt the data storage ecosystem by reducing the need to create new formats when hardware or encoding evolves, potentially simplifying data interchange across platforms. Its embedded WASM decoders ensure long-term readability and portability, challenging Parquet's dominance. Each F3 file includes data, metadata, and Wasm binaries for decoding, requiring only kilobytes of extra storage. The format is designed to be extensible, allowing developers to add new encoding schemes via a general-purpose API.

hackernews · tosh · Jun 23, 16:53 · [Discussion](https://news.ycombinator.com/item?id=48647799)

**Background**: Columnar storage formats like Parquet are widely used in big data systems for efficient compression and query performance. However, they require native decoders for each platform, limiting compatibility when new encoding schemes emerge. F3 addresses this by embedding Wasm decoders, which can run on any platform with a Wasm runtime.

<details><summary>References</summary>
<ul>
<li><a href="https://dl.acm.org/doi/10.1145/3749163">F3: The Open-Source Data File Format for the Future | Proceedings of the ACM on Management of Data</a></li>
<li><a href="https://db.cs.cmu.edu/papers/2025/zeng-sigmod2025.pdf">F3: The Open-Source Data File Format for the Future</a></li>
<li><a href="https://db.cs.cmu.edu/projects/future-file-formats/">Future File Formats - Carnegie Mellon Database Group</a></li>

</ul>
</details>

**Discussion**: The community is divided: some praise the WASM decoder approach as genius for ensuring compatibility, while others criticize the lack of clear 'why' and question the practical benefits over Parquet. Skeptics argue that embedding decoders doesn't solve interoperability at the application level, and the format faces an uphill battle for adoption.

**Tags**: `#data-format`, `#columnar-storage`, `#parquet`, `#wasm`, `#storage`

---

<a id="item-19"></a>
## [Digital Euro Gains EU Parliamentary Backing](https://finance.yahoo.com/markets/currencies/articles/ecb-secures-key-parliamentary-backing-102718449.html) ⭐️ 7.0/10

The European Central Bank has secured key parliamentary backing for the digital euro, moving the project closer to a potential launch by 2029. This development aims to reduce Europe's reliance on US-based credit card networks like Visa and Mastercard, potentially reshaping the global digital payments landscape. The digital euro would be a central bank digital currency (CBDC) issued by the ECB, available free of charge for basic use, and designed to complement cash rather than replace it.

hackernews · madars · Jun 23, 16:27 · [Discussion](https://news.ycombinator.com/item?id=48647444)

**Background**: A central bank digital currency (CBDC) is a digital form of a country's official currency, issued and backed by the central bank, unlike cryptocurrencies which are private. The digital euro project was launched in July 2021 and has completed its preparation phase; assuming legislation is adopted in 2026, testing could begin in mid-2027 with a potential launch by 2029.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Digital_euro">Digital euro</a></li>
<li><a href="https://www.ecb.europa.eu/euro/digital_euro/html/index.en.html">Digital euro - European Central Bank</a></li>
<li><a href="https://en.wikipedia.org/wiki/Central_bank_digital_currency">Central bank digital currency - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters raised concerns about the digital euro's ability to replace credit card features like fraud protection and chargebacks, and questioned why the EU doesn't develop a system similar to India's RuPay or Brazil's Pix instead of jumping to a CBDC.

**Tags**: `#digital currency`, `#EU regulation`, `#payments`, `#fintech`, `#CBDC`

---

<a id="item-20"></a>
## [IBM's CUGA: Lightweight Harness for Agentic Apps with 24 Examples](https://huggingface.co/blog/ibm-research/cuga-apps) ⭐️ 7.0/10

IBM Research has released CUGA (Configurable Generalist Agent), a lightweight harness for building agentic applications, along with two dozen working examples on Hugging Face. CUGA provides a practical, open-source alternative to brittle agent frameworks, enabling developers to build trustworthy, policy-aware automation with minimal overhead. CUGA combines ReAct, CodeAct, and Planner-Executor patterns into a modular architecture, and currently leads the AppWorld benchmark with 750 real-world tasks across 457 APIs.

rss · Hugging Face Blog · Jun 23, 12:51

**Background**: Agentic applications are AI systems that can autonomously plan and execute tasks using tools and APIs. Many existing frameworks are tightly coupled and struggle with tool misuse or long-horizon reasoning. CUGA addresses these issues with a configurable, lightweight harness that supports open models and real workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://research.ibm.com/blog/cuga-agent-framework">Introducing CUGA: The enterprise-ready configurable generalist agent - IBM Research</a></li>
<li><a href="https://dev.to/aairom/introducing-cuga-1p3k">📯Introducing CUGA - DEV Community</a></li>
<li><a href="https://www.infoq.com/news/2025/12/ibm-cuga/">IBM Research Introduces CUGA, an Open-Source Configurable Agent Framework on Hugging Face - InfoQ</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#CUGA`, `#IBM Research`, `#agentic apps`, `#Hugging Face`

---

<a id="item-21"></a>
## [Hugging Face's AI-Assisted Weekly Release Pipeline](https://huggingface.co/blog/huggingface-hub-release-ci) ⭐️ 7.0/10

Hugging Face detailed their CI/CD pipeline for weekly releases of the huggingface_hub library, which integrates AI tools for tasks like changelog generation and code review, while keeping a human in the loop for final approval. This approach demonstrates a practical, scalable workflow for maintaining a widely-used open-source library, balancing automation with human oversight to ensure quality and reliability. The pipeline uses AI to generate release notes and suggest code changes, but all releases require human review before deployment. The blog emphasizes that the human-in-the-loop model reduces manual effort while maintaining control.

rss · Hugging Face Blog · Jun 23, 00:00

**Background**: huggingface_hub is a Python library that provides a unified interface to the Hugging Face Hub, enabling users to share, download, and manage machine learning models, datasets, and other artifacts. It originated from extracting internal logic from the transformers library and has become a foundational tool for open machine learning. CI/CD (Continuous Integration/Continuous Deployment) pipelines automate the building, testing, and deployment of software, and integrating AI tools can further streamline these processes.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/huggingface-hub-v1">huggingface_hub v1.0: Five Years of Building the Foundation of Open Machine Learning</a></li>
<li><a href="https://teamvoy.com/blog/building-ai-agents-into-your-ci-cd-pipeline-a-playbook-for-tech-leads/">AI Agents in CI/CD Pipelines: A Guide for Tech Leads | Teamvoy</a></li>
<li><a href="https://northflank.com/blog/top-ai-tools-cicd-pipeline-automation">Top AI tools for CI/CD pipeline automation in 2026 | Blog — Northflank</a></li>

</ul>
</details>

**Tags**: `#CI/CD`, `#huggingface`, `#AI tools`, `#release engineering`, `#open source`

---

<a id="item-22"></a>
## [Hugging Face Tests Cross-Origin Storage API for Browser ML](https://huggingface.co/blog/cross-origin-storage) ⭐️ 7.0/10

Hugging Face has experimented with the proposed Cross-Origin Storage (COS) API to enable efficient caching of machine learning models in the browser using Transformers.js. This addresses a key bottleneck for client-side AI by allowing large models to be cached across origins, reducing load times and enabling more powerful web-based ML applications. The COS API provides a cross-origin file storage and retrieval mechanism for web applications, enabling storage of large files like AI models, SQLite databases, and Wasm modules across different origins securely.

rss · Hugging Face Blog · Jun 23, 00:00

**Background**: Transformers.js is a JavaScript library that allows running transformer-based machine learning models directly in the browser. However, loading large models from different origins is currently limited by browser storage policies, making caching inefficient. The Cross-Origin Storage API, proposed by Google, aims to solve this by providing a standardized way to store and access files across origins.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/explainers-by-googlers/cross-origin-storage">GitHub - explainers-by-googlers/cross-origin-storage: Explainer for the Cross-Origin Storage (COS) API</a></li>
<li><a href="https://wicg.github.io/cross-origin-storage/">Explainer for the Cross-Origin Storage (COS) API | cross-origin-storage</a></li>

</ul>
</details>

**Tags**: `#web-apis`, `#machine-learning`, `#transformers.js`, `#browser-storage`, `#cross-origin`

---

<a id="item-23"></a>
## [OpenAI Joins Appia Foundation for AI Standards](https://openai.com/index/helping-build-shared-standards-for-advanced-ai) ⭐️ 7.0/10

OpenAI announced its contribution to the Appia Foundation, an initiative under the Linux Foundation, to develop shared standards, evaluation frameworks, and safety practices for advanced AI. This collaboration signals a major industry push toward standardized AI safety and interoperability, which could accelerate responsible AI deployment and global regulatory alignment. The Appia Foundation focuses on creating modular open-source specifications and conformity assessment frameworks for the AI value chain, enabling organizations to demonstrate compliance with applicable obligations.

rss · OpenAI Blog · Jun 23, 13:00

**Background**: The Appia Foundation was recently launched by the Linux Foundation under the Joint Development Foundation to establish standardized conformity specifications across the global AI value chain. OpenAI's involvement adds significant weight to this effort, given its leading role in advanced AI development.

<details><summary>References</summary>
<ul>
<li><a href="https://appiafoundation.org/">Appia Foundation</a></li>
<li><a href="https://www.linuxfoundation.org/press/linux-foundation-launches-appia-foundation-to-establish-standardized-conformity-specifications-across-the-ai-value-chain">Linux Foundation Launches Appia Foundation to Establish Standardized Conformity Specifications Across the AI Value Chain</a></li>

</ul>
</details>

**Tags**: `#AI Safety`, `#Standards`, `#OpenAI`, `#Global Cooperation`

---

<a id="item-24"></a>
## [Jerry's Map: Hand-Drawn Imaginary Land Since 1963](http://www.jerrysmap.com/the-map) ⭐️ 6.0/10

Jerry has been hand-drawing a map of an imaginary land since 1963 using a card-based procedural system, and a web-based implementation has been created by the community. This project demonstrates a unique blend of procedural generation and long-term creative dedication, inspiring others to explore similar systematic world-building approaches. The map is generated by drawing cards from a deck that dictate terrain features, making the process feel like observing a system over decades rather than pure drawing.

hackernews · turtleyacht · Jun 23, 18:40 · [Discussion](https://news.ycombinator.com/item?id=48649435)

**Background**: Procedural generation uses algorithms or rules to create content automatically, often seen in video games for generating levels or maps. Jerry's card-based system is a low-tech, manual version of this concept.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Procedural_generation">Procedural generation - Wikipedia</a></li>
<li><a href="http://www-cs-students.stanford.edu/~amitp/game-programming/polygon-map-generation/">Polygonal Map Generation for Games</a></li>

</ul>
</details>

**Discussion**: Commenters expressed fascination with the card-based procedure, with one noting it makes the map feel like a system being observed. Another shared a web-based implementation, and a video by People Make Games was referenced.

**Tags**: `#procedural generation`, `#creative coding`, `#map making`, `#long-term project`

---

<a id="item-25"></a>
## [Germany Train Halt Due to Radio System Outage](https://apnews.com/article/germany-trains-halted-communications-radio-problem-deutsche-bahn-e8fd970b2d889f3ae7ce03322d5c726b) ⭐️ 6.0/10

On August 15, 2023, Deutsche Bahn halted all train services nationwide due to a failure of the GSM-R digital rail radio system, affecting long-distance, regional, and S-Bahn trains. This outage disrupted travel for millions and highlights the vulnerability of critical infrastructure reliant on specialized communication systems like GSM-R, which is integral to the European Rail Traffic Management System (ERTMS). The GSM-R system is used for voice and data communication between train drivers and signalers, and its failure forced trains to be held at stations for safety reasons. Deutsche Bahn technicians worked to resolve the issue, but no root cause was immediately confirmed.

hackernews · sva_ · Jun 23, 21:19 · [Discussion](https://news.ycombinator.com/item?id=48651613)

**Background**: GSM-R (Global System for Mobile Communications – Railway) is a secure digital communication standard for railways, part of the ERTMS. It replaces older analog systems and enables high-speed train operations with safety-critical signaling. A nationwide outage is rare and can cause cascading delays across the network.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GSM-R">GSM-R - Wikipedia</a></li>
<li><a href="https://www.dw.com/en/deutsche-bahn-halts-trains-across-germany-due-to-malfunctioning-radio-system/a-77682758">Deutsche Bahn halts trains nationwide amid IT meltdown</a></li>
<li><a href="https://www.independent.co.uk/news/world/europe/germany-trains-outage-stopped-deutsche-bahn-b3001705.html">All trains across Germany stopped due to nationwide outage | The Independent</a></li>

</ul>
</details>

**Discussion**: Community comments speculated on causes: some suspected a buggy software update, while others considered a cyber attack, though many noted Deutsche Bahn's history of technical issues. A comment also linked a recent UK train crash to possible sabotage, but no evidence supports this connection.

**Tags**: `#infrastructure`, `#outage`, `#railway`, `#GSM-R`, `#Germany`

---

<a id="item-26"></a>
## [Mistral Launches OCR 4 Amid Benchmark Skepticism](https://mistral.ai/news/ocr-4/) ⭐️ 6.0/10

Mistral AI has released OCR 4, a new optical character recognition model that claims state-of-the-art accuracy at a low cost of $4 per 1,000 pages, with support for structured output and self-hosting. This release could lower the barrier for high-quality document digitization, but community skepticism about benchmark validity and comparisons to existing tools like Baidu's Unlimited-OCR may limit its adoption. Mistral acknowledges that OlmOCRBench and OmniDocBench have known limitations, such as ground-truth errors and reading-order assumptions, and reports flagship numbers from its own internal benchmark instead.

hackernews · meetpateltech · Jun 23, 14:03 · [Discussion](https://news.ycombinator.com/item?id=48645152)

**Background**: Optical Character Recognition (OCR) converts images of text into machine-readable text. Benchmarks like OlmOCRBench and OmniDocBench are used to evaluate OCR models, but they can penalize correct outputs due to formatting variations or reading-order issues, making comparisons difficult.

<details><summary>References</summary>
<ul>
<li><a href="https://mistral.ai/news/ocr-4/">Mistral OCR 4 : SOTA OCR for Document Intelligence</a></li>
<li><a href="https://aiweekly.co/alerts/mistral-launches-ocr-4-with-structured-output-and-self-hosting">Mistral Launches OCR 4 With Structured Output and Self-Hosting | AI Weekly</a></li>
<li><a href="https://www.docsumo.com/blogs/ocr/docsumo-ocr-benchmark-report">Docsumo OCR Benchmark: Outperforming Mistral & Landing AI</a></li>

</ul>
</details>

**Discussion**: Community comments express skepticism about Mistral's benchmark claims, with one user noting that previous versions were '98% accurate based on internal benchmarks of 4 PDFs' and fell short in practice. Others question the use of truncated y-axes in bar charts and compare the release to Baidu's Unlimited-OCR.

**Tags**: `#OCR`, `#AI`, `#Mistral`, `#benchmarking`

---

<a id="item-27"></a>
## [OPFS + Pyodide Test Harness for Datasette Lite](https://simonwillison.net/2026/Jun/23/opfs-pyodide/#atom-everything) ⭐️ 6.0/10

Simon Willison built a test harness that combines the Origin Private File System (OPFS) with Pyodide to explore editing persistent SQLite files in the browser for Datasette Lite. This could enable Datasette Lite to edit persistent local SQLite databases entirely in the browser, expanding its utility for offline or privacy-sensitive data work. The harness is a playground UI built with Claude Code for web, allowing testing across different browsers. OPFS provides low-level, byte-by-byte file access without the security overhead of the File System Access API.

rss · Simon Willison · Jun 23, 18:58

**Background**: Datasette Lite runs the Python Datasette application in the browser via Pyodide and WebAssembly. OPFS is a browser storage API that allows web apps to store and manipulate files privately per origin, without user-visible file system access.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/File_System_API/Origin_private_file_system">Origin private file system - Web APIs | MDN</a></li>
<li><a href="https://developer.chrome.com/docs/capabilities/web-apis/file-system-access">The File System Access API: simplifying access to local files</a></li>
<li><a href="https://pyodide.org/en/stable/console.html">pyodide .org/en/stable/console.html</a></li>

</ul>
</details>

**Tags**: `#webassembly`, `#pyodide`, `#datasette`, `#browser-storage`

---