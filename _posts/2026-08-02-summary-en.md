---
layout: default
title: "Horizon Summary: 2026-08-02 (EN)"
date: 2026-08-02
lang: en
---

> From 19 items, 16 important content pieces were selected

---

1. [Go 1.27 Interactive Tour Highlights Generics and Runtime Fixes](#item-1) ⭐️ 8.0/10
2. [Diátaxis Framework Gains Traction with Translations and Community Adoption](#item-2) ⭐️ 8.0/10
3. [Open Letters on AI Development: Industry vs. Safety](#item-3) ⭐️ 8.0/10
4. [OpenAI's Astra Solves 10 Decade-Old Math Problems for $2,000 Each](#item-4) ⭐️ 8.0/10
5. [How Essential English Vocabulary for Learners Has Shifted (1953–2023)](#item-5) ⭐️ 7.0/10
6. [F*: A General-Purpose Proof-Oriented Programming Language](#item-6) ⭐️ 7.0/10
7. [Meshdiff: Client-Side STL Comparison Tool](#item-7) ⭐️ 7.0/10
8. [Bor: Open-Source Real-Time Policy Management for Linux Desktops](#item-8) ⭐️ 7.0/10
9. [15-Year-Old Builds Cycloidal Gearbox, Earns Community Praise](#item-9) ⭐️ 7.0/10
10. [Le Guin's 2005 Essay Redefines Technology Beyond Electronics](#item-10) ⭐️ 7.0/10
11. [Karpathy Stars sqliteai/waste: A New MoE Inference Engine](#item-11) ⭐️ 6.0/10
12. [RISC OS Open Celebrates 20 Years of Niche ARM OS Development](#item-12) ⭐️ 6.0/10
13. [Karpathy's LLM-Generated 3D Animation Sparks Benchmark Debate](#item-13) ⭐️ 6.0/10
14. [Medieval Ars Notoria as a Historical Mirror for AI's Promise of Instant Knowledge](#item-14) ⭐️ 6.0/10
15. [MkLinux on Apple Workgroup Server 9150: A Nostalgic Retrocomputing Tale](#item-15) ⭐️ 6.0/10
16. [Greg Brockman: People Dislike Coworker ChatGPT on Slack](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Go 1.27 Interactive Tour Highlights Generics and Runtime Fixes](https://victoriametrics.com/blog/go-1-27/index.html) ⭐️ 8.0/10

An interactive tour of Go 1.27 has been published, showcasing key features such as generic methods, JSON v2, native UUID support, and runtime fixes. The tour is designed to help developers understand the changes through hands-on examples. Go 1.27 is a significant release that introduces long-awaited features like generic methods, which will simplify code and improve developer productivity. The runtime fixes, including compatibility with Android's MTE, enhance security and reliability for mobile and system-level applications. The tour highlights generic methods, which allow methods to declare their own type parameters, a feature that was previously limited to functions. It also covers the new json/v2 package, native UUID support, and a goroutine-leak profiler, along with a fix for runtime.findnull() to be compatible with MTE on Android.

hackernews · Hixon10 · Aug 2, 01:35 · [Discussion](https://news.ycombinator.com/item?id=49140218)

**Background**: Go is a statically typed, compiled programming language designed for simplicity and efficiency. Generics were introduced in Go 1.18, but methods could not have their own type parameters until now. The Go 1.27 release also includes changes to the standard library and runtime, reflecting the language's ongoing evolution.

<details><summary>References</summary>
<ul>
<li><a href="https://go.dev/doc/go1.27">Go 1.27 Release Notes - The Go Programming Language</a></li>
<li><a href="https://ademawan.medium.com/go-1-27-is-coming-what-many-developers-have-been-waiting-for-afcdfa00a8a4">Go 1.27 Is Coming: What Many Developers Have Been Waiting For</a></li>
<li><a href="https://medium.com/@arthurpro/go-1-27-is-coming-generic-methods-json-v2-and-more-749d08192f5a">Go 1.27 Is Coming: Generic Methods, json/v2, and more</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed reactions: some developers find the new generic method syntax confusing, while others appreciate the runtime fixes, such as MTE compatibility. There are also concerns about the silent behavior change of automatically draining HTTP response bodies, which could affect existing applications.

**Tags**: `#Go`, `#programming language`, `#release`, `#generics`, `#runtime`

---

<a id="item-2"></a>
## [Diátaxis Framework Gains Traction with Translations and Community Adoption](https://diataxis.fr/) ⭐️ 8.0/10

Diátaxis, a framework for organizing technical documentation into four types, has gained significant community attention (484 points, 56 comments on Hacker News). The author, Daniele Procida, announced ongoing translations into multiple languages, with an in-progress version available at diataxis-translated.readthedocs.io. This framework provides a systematic approach to documentation that many teams find valuable, improving clarity and consistency. Its growing adoption and translation efforts indicate a broad need for better documentation practices in software engineering. The framework categorizes documentation into tutorials, how-to guides, reference, and explanation, each serving a distinct user need. The author's translation project aims to make the framework accessible to non-English speakers, with partial translations already available.

hackernews · ryanseys · Aug 1, 20:33 · [Discussion](https://news.ycombinator.com/item?id=49138188)

**Background**: Diátaxis is a pragmatic and systematic approach to creating documentation, widely adopted in the tech industry. It helps writers structure content by user needs, avoiding common pitfalls like mixing tutorials with reference material. The framework is often compared to other documentation methodologies like DITA and Information Mapping.

<details><summary>References</summary>
<ul>
<li><a href="https://diataxis.fr/">Diátaxis</a></li>
<li><a href="https://idratherbewriting.com/blog/what-is-diataxis-documentation-framework">What is Diátaxis and should you be using it with your ...</a></li>
<li><a href="https://github.com/evildmp/diataxis-documentation-framework">GitHub - evildmp/diataxis-documentation-framework: A systematic approach to creating better documentation. · GitHub</a></li>

</ul>
</details>

**Discussion**: Community members shared positive experiences, with one noting it was 'fantastic' for documenting a complex codebase, though requiring effort to plan page titles. Another cautioned not to take it as 'gospel' but found it helpful, advising to read the website thoroughly before starting. Some also noted it has been posted multiple times before.

**Tags**: `#documentation`, `#technical-writing`, `#software-engineering`, `#framework`

---

<a id="item-3"></a>
## [Open Letters on AI Development: Industry vs. Safety](https://simonwillison.net/2026/Aug/2/open-letters/#atom-everything) ⭐️ 8.0/10

Simon Willison summarized recent open letters on AI development, notably Microsoft's 'Open Weights and American AI Leadership' signed by 235 companies including NVIDIA, Amazon, and OpenAI, and Anthropic's counter-response. Additionally, 'Pacing the Frontier' was published with signatures from 1,324 employees of frontier AI companies. These letters highlight a significant industry divide on AI safety and open-source models, influencing potential U.S. policy. The outcome could shape the future of AI development, balancing innovation and safety, and affect global competitiveness. Microsoft's letter argues that open-weight models are safer than closed ones, citing single points of failure, and supports distillation as a legitimate technique. Anthropic, notably absent from the letter, warns of risks like cyberattacks and calls for cracking down on industrial-scale distillation, while not advocating a ban. 'Pacing the Frontier' requests international efforts to pace automated AI development.

rss · Simon Willison · Aug 2, 04:16

**Background**: Open-weight models are AI models whose weights are publicly released, allowing anyone to use, modify, and study them. The debate centers on whether such openness poses safety risks, such as misuse by malicious actors, or whether it fosters innovation and transparency. The U.S. government has considered restrictions on open-weight models over safety concerns, prompting industry responses.

<details><summary>References</summary>
<ul>
<li><a href="https://www.microsoft.com/en-us/corporate-responsibility/wp-content/uploads/2026/07/open-weight-models-letter_July26.pdf">Open Weights and American AI Leadership</a></li>
<li><a href="https://www.cnbc.com/2026/07/24/nvidia-microsoft-meta-open-weight-ai-models.html">Nvidia, Microsoft, Meta warn against 'premature restrictions' of open-weight models</a></li>
<li><a href="https://www.semafor.com/article/07/28/2026/chinese-open-weight-models-reignite-ai-safety-debate">Chinese open-weight models reignite AI safety debate | Semafor</a></li>

</ul>
</details>

**Discussion**: The discussion reflects a split: some support the open letter's stance that open weights enhance security and innovation, while others echo Anthropic's concerns about potential misuse. There is also debate over the influence of major companies on policy and the balance between safety and progress.

**Tags**: `#AI policy`, `#open source`, `#AI safety`, `#industry influence`

---

<a id="item-4"></a>
## [OpenAI's Astra Solves 10 Decade-Old Math Problems for $2,000 Each](https://simonwillison.net/2026/Aug/1/ten-advances-in-mathematics/#atom-everything) ⭐️ 8.0/10

On August 1, 2026, OpenAI announced that an internal version of its next major model, Astra, solved ten long-standing mathematical problems that had seen no progress for at least a decade. The company claims each solution cost less than $2,000 at GPT-5.6 Sol token prices, and they released Lean 4 formalizations and a paper describing the results. This marks a significant milestone in AI-assisted mathematics, demonstrating that frontier models can tackle long-standing open problems at remarkably low cost. It could accelerate research in mathematics and theoretical computer science, shifting the role of mathematicians toward creative problem framing while AI handles technical details, as envisioned by Terence Tao's 'big mathematics'. The results are formalized in the openai/ten-proofs GitHub repository using Lean 4, and OpenAI also released a paper and an LLM-generated PDF that reconstructs the reasoning traces. However, the post notes that OpenAI did not disclose how many problems they attempted without success, and the prompts used were not published.

rss · Simon Willison · Aug 1, 20:34

**Background**: Lean 4 is an interactive theorem prover that allows mathematical proofs to be verified by a computer, ensuring correctness. GPT-5.6 is OpenAI's latest model family with three tiers—Sol, Terra, and Luna—priced per million tokens, with Sol being the most expensive at $5 input and $30 output. This announcement follows Anthropic's Claude Mythos Preview discovering cryptographic weaknesses, highlighting a trend of AI models making significant research contributions.

<details><summary>References</summary>
<ul>
<li><a href="https://byteiota.com/openai-astra-multi-agent-model/">OpenAI Astra: Multi-Agent Model Solves 10 Decade-Old Math ...</a></li>
<li><a href="https://techwafer.com/openai-astra-solved-10-open-math-problems-for-2000/">OpenAI Astra: 10 Math Problems Solved for $2,000, Explained</a></li>
<li><a href="https://www.eesel.ai/blog/gpt-5-6-pricing">GPT-5.6 pricing (2026): Sol, Terra, and Luna costs explained</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion likely includes a mix of awe and skepticism, with some praising the transparency of releasing formal proofs while others questioning the undisclosed failures and the lack of prompt transparency. The post itself notes a 'collective burst of Deep Blue' among mathematicians, referencing a spiritual crisis described in Kirwin Hampshire's essay.

**Tags**: `#AI`, `#mathematics`, `#OpenAI`, `#research`, `#theoretical computer science`

---

<a id="item-5"></a>
## [How Essential English Vocabulary for Learners Has Shifted (1953–2023)](https://pudding.cool/2026/07/essential-words/) ⭐️ 7.0/10

The Pudding published a data-driven analysis showing how the essential vocabulary taught to English language learners has changed from 1953 to 2023, revealing significant shifts in word lists. Nearly a quarter of the 1953 words are gone, and 39% of the 2023 words are new. This analysis highlights how language teaching reflects broader cultural and social changes, offering insights for educators and linguists. It underscores the dynamic nature of language and the need to update curricula to meet contemporary communication needs. The article categorizes vocabulary into levels such as 'Social-Communicative,' noting that while its size barely changed, the composition shifted dramatically. Words like 'humble,' 'loyalty,' and 'fellowship' gave way to 'community,' 'identity,' and 'gender,' indicating a move from interpersonal virtues to broader social constructs.

hackernews · c-oreills · Aug 2, 15:41 · [Discussion](https://news.ycombinator.com/item?id=49145590)

**Background**: English language teaching often relies on curated word lists to prioritize vocabulary for learners. These lists are based on frequency and usefulness, but they also implicitly reflect cultural values and priorities of the time. The Pudding's analysis uses historical textbooks and frequency data to track these changes over seven decades.

**Discussion**: Commenters discussed the difficulty of creating such lists, noting that vocabulary priorities vary by purpose (e.g., travel vs. TV vs. newspaper). Some attributed the shift to rising inequality and 'tribalization,' while others debated the scroll behavior of the webpage, showing diverse perspectives on the analysis and its presentation.

**Tags**: `#linguistics`, `#education`, `#data-analysis`, `#culture`, `#language-learning`

---

<a id="item-6"></a>
## [F*: A General-Purpose Proof-Oriented Programming Language](https://fstar-lang.org/) ⭐️ 7.0/10

F* is a mature, general-purpose proof-oriented programming language that supports formal verification through dependent types, SMT solving, and tactic-based theorem proving. It enables incremental migration of existing C codebases to a formally verified environment. F* bridges the gap between practical programming and formal verification, allowing developers to prove properties about their code while maintaining performance and interoperability with C. This is significant for safety-critical systems in industries like aerospace, cryptography, and blockchain, where correctness is paramount. F* combines purely functional and effectful programming, leveraging dependent types and SMT-based automation. It has been used in real-world projects like the Everest project for verified HTTPS, and its GitHub repository shows active development.

hackernews · ducktective · Aug 2, 12:31 · [Discussion](https://news.ycombinator.com/item?id=49143925)

**Background**: Formal verification is the process of mathematically proving that a system meets its specification. F* is inspired by ML, Caml, and OCaml, and is designed to support both functional and effectful programming while enabling proofs. It uses SMT solvers and interactive theorem proving to automate parts of the verification process, making it more accessible to developers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/F*_(programming_language)">F* (programming language) - Wikipedia</a></li>
<li><a href="https://fstar-lang.org/">F*: A Proof-Oriented Programming Language</a></li>
<li><a href="https://github.com/FStarLang/FStar">GitHub - FStarLang/FStar: A Proof-oriented Programming Language · GitHub</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed sentiment: some users criticize the lack of syntax examples on the homepage, while others praise its capability for incremental C migration. There are also questions about its suitability for compiler verification and comparisons to other proof assistants like Lean.

**Tags**: `#formal verification`, `#programming language`, `#proof-oriented`, `#F*`, `#functional programming`

---

<a id="item-7"></a>
## [Meshdiff: Client-Side STL Comparison Tool](https://meshdiff.com/) ⭐️ 7.0/10

Meshdiff is a new browser-based tool that allows users to visually compare two versions of an STL file entirely on the client side, without uploading data to a server. It provides three viewports to inspect differences, and the community has suggested features like synchronized rotation and CI integration. This tool addresses a practical need in 3D printing and CAD workflows, where tracking changes to 3D models is often cumbersome. By running client-side, it enhances privacy and speed, and its potential integration into CI pipelines could automate visual regression testing for 3D files. Meshdiff uses client-side rendering, likely leveraging WebGL or Three.js, to display STL meshes. The tool currently offers three viewports for side-by-side comparison, and the community has proposed features such as synchronized transforms and a CLI for CI integration.

hackernews · projscope · Aug 2, 11:34 · [Discussion](https://news.ycombinator.com/item?id=49143479)

**Background**: STL is a file format commonly used for 3D printing and CAD, representing surface geometry as a triangulated mesh. Client-side rendering processes web content in the browser using JavaScript, which can improve privacy and performance by avoiding server uploads. Tools like Meshdiff are part of a growing trend of in-browser applications powered by WebAssembly and Three.js.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/STL_(file_format)">STL (file format)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Client-side_rendering">Client-side rendering</a></li>

</ul>
</details>

**Discussion**: The community response is positive, with users praising the tool's utility and client-side approach. Suggestions include adding synchronized viewport rotation, locking views together, and integrating Meshdiff into CI pipelines or as a GitHub PR trigger for 3D files. Some users also recommended related projects in the BIM and architecture space.

**Tags**: `#3D`, `#STL`, `#visualization`, `#client-side`, `#developer tools`

---

<a id="item-8"></a>
## [Bor: Open-Source Real-Time Policy Management for Linux Desktops](https://getbor.dev/blog/2026-08-02-bor-v080-release/) ⭐️ 7.0/10

Bor, an open-source centralized policy management system for Linux desktops, released version 0.8, adding support for Thunderbird, Microsoft Edge for Business, and FirewallD zones. It uses a Go agent and server to stream policies in real time over mTLS/gRPC, eliminating polling. This addresses a significant gap in Linux desktop management, offering a modern, real-time alternative to traditional tools. It could benefit organizations managing fleets of Linux workstations, especially those seeking open-source solutions to avoid proprietary systems like Windows Intune. Bor's architecture uses a lightweight Go agent on clients and a central server, with policies streamed over mTLS/gRPC in real time. Version 0.8 introduces new policy types, and the system currently supports Firefox, Chrome, KDE, dconf, polkit, and package management, with more planned.

hackernews · eniac111 · Aug 2, 09:06 · [Discussion](https://news.ycombinator.com/item?id=49142569)

**Background**: Linux desktop management often relies on manual configuration or tools like Ansible, which use periodic polling or push-based deployment. dconf is a configuration database used by GNOME for settings, while polkit controls system-wide privileges. mTLS (mutual TLS) ensures both client and server authenticate each other, and gRPC is a high-performance RPC framework that supports streaming.

<details><summary>References</summary>
<ul>
<li><a href="https://help.gnome.org/system-admin-guide/dconf.html">Manage user and system settings with dconf - GNOME</a></li>
<li><a href="https://en.wikipedia.org/wiki/Polkit">Polkit - Wikipedia</a></li>
<li><a href="https://github.com/islishude/grpc-mtls-example">GitHub - islishude/ grpc - mtls -example: grpc mTLS example · GitHub</a></li>

</ul>
</details>

**Discussion**: Community feedback is positive, with users expressing interest for non-profit laptop management and asking about custom script execution and user mapping. Questions also compare Bor to tools like System76's Cosmic Sync and inquire about mTLS vs SSH, policy enforcement without polling, and competing solutions.

**Tags**: `#Linux`, `#desktop management`, `#policy management`, `#open-source`, `#Go`

---

<a id="item-9"></a>
## [15-Year-Old Builds Cycloidal Gearbox, Earns Community Praise](https://github.com/tom-ilan/cycloidal_gearbox) ⭐️ 7.0/10

A 15-year-old developer named Tom Ilan shared a self-built cycloidal gearbox project on Hacker News, complete with detailed documentation and manufacturing references. The project, hosted on GitHub, quickly gained traction with 285 points and 94 comments. This project highlights the potential of young makers in hardware engineering, demonstrating that age is not a barrier to creating complex mechanical devices. It also showcases the value of open-source documentation and community support in fostering STEM education and practical skills. The gearbox is a cycloidal drive, which uses an eccentric cam and cycloidal disc to achieve high reduction ratios with low backlash and compact size. The project includes references to established standards, indicating a focus on quality and manufacturability.

hackernews · tomilan · Aug 2, 02:07 · [Discussion](https://news.ycombinator.com/item?id=49140396)

**Background**: A cycloidal gearbox, also known as a cycloidal drive, is a type of speed reducer that uses cycloidal disc motion to achieve high reduction ratios. It works by rotating a cycloidal disc via an eccentric cam, which meshes with roller pins on a ring gear, providing smooth and efficient power transmission. These gearboxes are valued for their compactness, robustness, and low backlash, making them suitable for precision applications like robotics and industrial machinery.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cycloidal_drive">Cycloidal drive - Wikipedia</a></li>
<li><a href="https://howtomechatronics.com/how-it-works/what-is-cycloidal-driver-designing-3d-printing-and-testing/">What is Cycloidal Driver? Designing, 3D Printing and Testing</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S1110016824001182">Design principle and numerical analysis for cycloidal drive considering clearance, deformation, and friction - ScienceDirect</a></li>

</ul>
</details>

**Discussion**: The community response was overwhelmingly positive, with many commenters praising the young maker's craftsmanship and documentation. Several users encouraged him to drop the 'wannabe' label, asserting that he is already an engineer. Some also discussed the potential for such projects to lead to paid opportunities, bypassing traditional education paths.

**Tags**: `#mechanical engineering`, `#hardware`, `#DIY`, `#gearbox`, `#young maker`

---

<a id="item-10"></a>
## [Le Guin's 2005 Essay Redefines Technology Beyond Electronics](https://www.ursulakleguin.com/a-rant-about-technology) ⭐️ 7.0/10

Ursula K. Le Guin's 2005 essay 'A Rant About Technology' critiques the narrow modern usage of the term 'technology,' arguing it should encompass all human skills and knowledge, not just electronic devices. The essay has resurfaced on Hacker News, sparking substantive discussion. This essay challenges the tech community's self-perception, urging a broader understanding of technology that includes traditional crafts and knowledge. It resonates with ongoing debates about the definition and value of technology in society, influencing how we view innovation and progress. Le Guin defines technology as 'the active human interface with the material world,' contrasting it with the common misuse that limits it to recent complex technologies. The essay emphasizes that all technologies, from stone tools to computers, are learnable skills, and critiques the exploitation associated with modern tech.

hackernews · jamesgill · Aug 2, 14:51 · [Discussion](https://news.ycombinator.com/item?id=49145201)

**Background**: Ursula K. Le Guin was a renowned science fiction and fantasy author, known for works like the Earthsea series and 'The Left Hand of Darkness.' Her essay reflects a philosophical perspective that predates current discussions on technology's role, drawing on her background in anthropology and literature.

**Discussion**: Commenters praised Le Guin's precise language and humble sentiment, with one noting it distills the draw toward technical pursuits. Others drew parallels to Steve Jobs' final email about human interdependence, and discussed the blurred lines between sci-fi and fantasy, reflecting on how technology is perceived in fiction.

**Tags**: `#philosophy`, `#technology`, `#essay`, `#Ursula K. Le Guin`, `#science fiction`

---

<a id="item-11"></a>
## [Karpathy Stars sqliteai/waste: A New MoE Inference Engine](https://github.com/sqliteai/waste) ⭐️ 6.0/10

Andrej Karpathy starred the GitHub repository sqliteai/waste, which is an embeddable inference engine written in C that can run the full 2.78-trillion-parameter Kimi K3 model on systems with limited RAM by streaming activated weights from disk. This star from a prominent AI figure highlights the growing interest in running large models locally on consumer hardware, potentially democratizing access to frontier-scale AI models without requiring massive server infrastructure. WASTE has no third-party runtime dependencies, keeps the model trunk in memory, streams selected experts directly from disk, and uses remaining RAM as a bounded expert cache. The Kimi K3 model is 1.42 TB as published and 982 GB after conversion.

github · karpathy · Aug 2, 17:19

**Background**: Mixture-of-Experts (MoE) models activate only a subset of their parameters per token, allowing them to have a large total parameter count while keeping inference efficient. WASTE exploits this by storing the full model on disk and only loading the necessary experts into memory, enabling inference on systems with limited RAM.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/sqliteai/waste">GitHub - sqliteai / waste : Run the full 2.78-trillion-parameter Kimi...</a></li>
<li><a href="https://github.com/sqliteai/waste/blob/main/README.md">waste/README.md at main · sqliteai/waste · GitHub</a></li>
<li><a href="https://karpathy.ai/">Andrej Karpathy</a></li>

</ul>
</details>

**Tags**: `#github`, `#karpathy`, `#sqlite`, `#ai`, `#unknown`

---

<a id="item-12"></a>
## [RISC OS Open Celebrates 20 Years of Niche ARM OS Development](https://www.riscosopen.org/news/articles/2026/06/20/twenty-years-of-risc-os-open) ⭐️ 6.0/10

RISC OS Open (ROOL) celebrated its 20th anniversary on June 20, 2026, marking two decades of community-driven development and preservation of the RISC OS operating system. The milestone highlights the project's persistence in maintaining and evolving the ARM-based OS originally created by Acorn Computers. This anniversary underscores the enduring relevance of RISC OS within the retro-computing and open-source communities, demonstrating that a niche platform can survive and adapt long after its original creator ceased operations. It also highlights the ongoing interest in ARM-based systems and the value of community-led software preservation. RISC OS Open Limited (ROOL) manages the source code for RISC OS, which was fully open-sourced under the Apache 2.0 license in October 2018 after RISC OS Developments acquired the intellectual property from Castle Technology. The project also introduced a bounty scheme in 2011 to encourage further development, and it continues to support ARM-based hardware such as the Raspberry Pi.

hackernews · AlexeyBrin · Aug 2, 12:36 · [Discussion](https://news.ycombinator.com/item?id=49143967)

**Background**: RISC OS is a modular operating system designed in Cambridge, England by Acorn Computers, first released in 1987 for ARM-based processors. It takes its name from the RISC (Reduced Instruction Set Computer) architecture it supports and features a graphical user interface and windowing system. Despite Acorn's demise, RISC OS has been kept alive by the RISC OS Open community, which continues to develop version 5.0 of the system.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/RISC_OS">RISC OS - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/RISC_OS_Open">RISC OS Open - Wikipedia</a></li>
<li><a href="https://www.riscosopen.org/content/">RISC OS Open: Welcome RISC OS Open - Wikipedia Complete OS Guide: RISC OS Open How It Works, Orientation and ... RISC OS Open: About RISC OS in Library RISC OS Open - grokipedia.com RISC OS Has Been Released to Open Source – Open-Electronics</a></li>

</ul>
</details>

**Discussion**: Community comments reflect a mix of nostalgia and technical appreciation. One user shared personal history of developing software for RISC OS, noting it was where they learned open-source development, while another highlighted the surprising longevity of the project given how many users left before 2000. Others praised RISC OS's fast boot times on the Raspberry Pi and pointed to resources for programming on the platform.

**Tags**: `#RISC OS`, `#retro computing`, `#open source`, `#ARM`

---

<a id="item-13"></a>
## [Karpathy's LLM-Generated 3D Animation Sparks Benchmark Debate](https://twitter.com/karpathy/status/2083749667410727319) ⭐️ 6.0/10

Andrej Karpathy shared a tweet featuring an LLM-generated 3D animation, prompting discussions about using such outputs as benchmarks for physical world understanding. The animation, likely created via code generation, demonstrates the model's ability to interpret and render a scene. This highlights a shift from static image generation to dynamic 3D scenes as a new frontier for evaluating AI's physical world understanding. It could influence how researchers design benchmarks and assess model capabilities beyond text and images. The animation was generated by an LLM, likely through three.js code, and community members noted its janky quality and misinterpretation of text (e.g., Bilbo's disappearance). Some argue that such outputs serve as qualitative benchmarks for physical understanding, while others caution against overinterpreting model's code-generation skills.

hackernews · delichon · Aug 2, 04:05 · [Discussion](https://news.ycombinator.com/item?id=49140998)

**Background**: Large language models (LLMs) have recently advanced from generating text and images to producing code for 3D animations, often using libraries like three.js. Benchmarks like PhysBench and PAI-Bench are emerging to evaluate physical world understanding in vision-language models, but qualitative assessments of generated animations remain subjective.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Whalefishin/LLM_animation">GitHub - Whalefishin/LLM_animation: A showroom for various animations generated by large language models (LLM). Our method takes a rigged 3D model and produces novel animations specified via natural language descriptions in a matter of seconds. · GitHub</a></li>
<li><a href="https://arxiv.org/abs/2501.16411">[2501.16411] PhysBench: Benchmarking and Enhancing Vision ...</a></li>
<li><a href="https://github.com/SHI-Labs/physical-ai-bench">GitHub - SHI-Labs/physical-ai-bench: [CVPR 2026 Oral] PAI ...</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed reactions: some criticize the animation's quality and text understanding, while others defend it as a useful benchmark for physical world understanding. There is also skepticism about whether LLMs are specifically trained for three.js code, making such outputs less indicative of general intelligence.

**Tags**: `#LLM`, `#3D animation`, `#benchmark`, `#AI`, `#Karpathy`

---

<a id="item-14"></a>
## [Medieval Ars Notoria as a Historical Mirror for AI's Promise of Instant Knowledge](https://publicdomainreview.org/essay/ars-notoria/) ⭐️ 6.0/10

An essay in The Public Domain Review draws parallels between the medieval Ars Notoria, a grimoire promising instant knowledge through angelic magic, and modern AI's promise of instant knowledge. The essay explores how this historical text reflects enduring human desires for rapid learning and mastery. This comparison offers a fresh perspective on AI's cultural impact, highlighting that the promise of instant knowledge is not new but deeply rooted in human history. It encourages critical reflection on AI's limitations and the ethical implications of seeking shortcuts to expertise. The Ars Notoria is a medieval grimoire attributed to Solomon, containing prayers and 'notae' (sigils) believed to grant rapid learning of scholastic knowledge. The essay uses historical accounts, such as that of John of Morigny, to illustrate the allure and dangers of such magical shortcuts, drawing parallels to modern AI tools like knowledge bases.

hackernews · jruohonen · Aug 2, 10:18 · [Discussion](https://news.ycombinator.com/item?id=49143001)

**Background**: The Ars Notoria was part of the Solomonic magic tradition in medieval Europe, used by scholars seeking to master subjects like rhetoric and dialectic quickly. Modern AI, particularly large language models and knowledge management systems, similarly promises instant access to information and accelerated learning, raising questions about the nature of knowledge and the value of effortful study.

<details><summary>References</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=vv0plm9SVIo">Ars Notoria - Medieval Magic for Learning All Knowledge... - YouTube</a></li>
<li><a href="https://www.youtube.com/watch?v=oAld-W9spEA">Ars Notoria [Solomonic Magic - Full Grimoire] - YouTube</a></li>
<li><a href="https://www.abebooks.com/9781644115275/Ars-Notoria-Notory-Art-Solomon-1644115271/plp">Ars Notoria : The Notory Art of Solomon: A Medieval ... - AbeBooks</a></li>

</ul>
</details>

**Discussion**: Commenters found the historical parallels intriguing but noted the AI connection felt tenuous or baity. Some discussed the misnomer 'Chaldean' and the practical limitations of such magical shortcuts, contrasting them with the rigor required for modern technical fields like physics or CS. Others humorously linked the grimoire to Warhammer 40k lore.

**Tags**: `#history`, `#AI`, `#knowledge`, `#philosophy`, `#education`

---

<a id="item-15"></a>
## [MkLinux on Apple Workgroup Server 9150: A Nostalgic Retrocomputing Tale](http://oldvcr.blogspot.com/2026/08/mklinux-and-pimped-out-apple-workgroup.html) ⭐️ 6.0/10

A blog post recounts the author's experience running MkLinux on an Apple Workgroup Server 9150, detailing the technical challenges and the machine's unique hardware. The post highlights the historical significance of MkLinux as Apple's first open-source project. This nostalgic account sheds light on a pivotal moment in Apple's history when it embraced open-source software, influencing its future operating system strategy. It resonates with retrocomputing enthusiasts and provides insight into the early days of Linux on PowerPC hardware. The Apple Workgroup Server 9150 featured an 80 MHz PowerPC 601 processor (later bumped to 120 MHz) in a Quadra 900-style case, with a tape backup drive and a relocated floppy drive. MkLinux ran Linux as a user-space server on top of the Mach 3.0 microkernel, which offered stability but incurred performance overhead.

hackernews · goldenskye · Aug 2, 03:12 · [Discussion](https://news.ycombinator.com/item?id=49140702)

**Background**: MkLinux, short for Microkernel Linux, was an experimental open-source operating system launched in 1995 as a collaboration between the Open Software Foundation (OSF) and Apple Computer. It adapted the Linux kernel to run on top of the Mach microkernel, marking Apple's first official free and open-source software project. The Apple Workgroup Server 9150 was a high-end server model released in 1994, notable for its unique case design and PowerPC architecture.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MkLinux">MkLinux</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_Workgroup_Server_9150">Apple Workgroup Server 9150</a></li>
<li><a href="http://www.mklinux.org/">Welcome to MkLinux.org</a></li>

</ul>
</details>

**Discussion**: Community members shared personal anecdotes about using MkLinux on similar Power Macs, noting its stability compared to System 7 and the initial lack of multi-button mouse support. Some expressed nostalgia for the era, while others highlighted the performance trade-offs of the microkernel architecture.

**Tags**: `#MkLinux`, `#Apple`, `#retrocomputing`, `#Linux`, `#PowerPC`

---

<a id="item-16"></a>
## [Greg Brockman: People Dislike Coworker ChatGPT on Slack](https://simonwillison.net/2026/Aug/1/greg-brockman/#atom-everything) ⭐️ 6.0/10

Greg Brockman, President and Co-Founder of OpenAI, observed that at OpenAI, many employees connect their ChatGPT to Slack, but people strongly dislike being contacted by a coworker's ChatGPT for help, even if they would gladly help the coworker directly. This highlights a critical human-centric concern in AI integration: AI should enhance human relationships and give time back, not become a layer that separates people. It underscores the importance of designing AI tools that respect and augment human connections in the workplace. The observation comes from a tweet by Greg Brockman, shared on Simon Willison's blog. It reflects a real-world example of AI-mediated communication in a workplace setting, where the AI acts as an intermediary, potentially reducing the perceived human touch.

rss · Simon Willison · Aug 1, 22:29

**Background**: AI integration in workplace tools like Slack is becoming common, with ChatGPT offering native Slack integrations for summarization and assistance. However, this raises ethical questions about AI-mediated communication, as trust and human relationships are fundamental to effective collaboration. Brockman's comment suggests that while AI can be helpful, it must not replace the human element in interactions.

<details><summary>References</summary>
<ul>
<li><a href="https://clearfeed.ai/blogs/chatgpt-slack-integration-guide">ChatGPT Slack Integration : What the App Does Well (and Where...)</a></li>
<li><a href="https://journals.sagepub.com/doi/10.1177/15480518241289644">Artificial Intelligence (AI) and Workplace Communication ...</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#human-AI interaction`, `#workplace AI`, `#OpenAI`, `#generative AI`

---