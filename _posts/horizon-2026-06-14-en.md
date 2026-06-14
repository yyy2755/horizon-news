# Horizon Daily - 2026-06-14

> From 14 items, 13 important content pieces were selected

---

1. [Pyodide 314.0: Publish WASM wheels directly to PyPI](#item-1) ⭐️ 9.0/10
2. [Honda Civic Infotainment Vulnerable via AOSP Test Keys](#item-2) ⭐️ 8.0/10
3. [GLM 5.2 Fully Open Frontier Model Released by Z.ai](#item-3) ⭐️ 8.0/10
4. [Census Bureau Bans Noise Infusion in Statistical Products](#item-4) ⭐️ 8.0/10
5. [New Pancreatic Cancer Drug Doubles Survival](#item-5) ⭐️ 8.0/10
6. [Phoenix LiveView 1.2 Released](#item-6) ⭐️ 8.0/10
7. [Amazon CEO's Talks Led to U.S. Crackdown on Anthropic AI](#item-7) ⭐️ 8.0/10
8. [Running DOS on Behringer DDX3216 with Custom BIOS](#item-8) ⭐️ 8.0/10
9. [Large Context Windows in LLMs Are Unreliable](#item-9) ⭐️ 7.0/10
10. [Mapping SQLite Result Columns to Source Tables](#item-10) ⭐️ 7.0/10
11. [Free Browser-Based SQL to ER Diagram Tool](#item-11) ⭐️ 6.0/10
12. [Game Boy Workboy Unreleased Addon Recovered](#item-12) ⭐️ 6.0/10
13. [luau-wasm 0.1a0: Lua Interpreter for Pyodide](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Pyodide 314.0: Publish WASM wheels directly to PyPI](https://simonwillison.net/2026/Jun/13/publishing-wasm-wheels/#atom-everything) ⭐️ 9.0/10

Pyodide 314.0 enables package maintainers to publish WebAssembly (WASM) wheels directly to PyPI, following PEP 783's PyEmscripten platform tag. Previously, over 300 packages had to be manually built and hosted by Pyodide maintainers. This removes a major bottleneck for Python-in-browser runtimes like Pyodide, enabling any package maintainer to distribute WASM-compiled packages without manual intervention. It significantly expands the ecosystem of Python packages available in the browser. The PyPI support landed via PR #19804 on April 21st, 2026. Simon Willison demonstrated the workflow by publishing luau-wasm, a 276KB wheel that runs the Luau language inside Pyodide, using cibuildwheel and GitHub Actions.

rss · Simon Willison · Jun 13, 23:55

**Background**: Pyodide is a Python distribution for the browser based on WebAssembly. Previously, distributing Python packages with C/Rust extensions required manual compilation and hosting by Pyodide maintainers. PEP 783 standardized the PyEmscripten platform tag, enabling automatic recognition of WASM wheels on PyPI.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/13/publishing-wasm-wheels/">Publishing WASM wheels to PyPI for use with Pyodide</a></li>
<li><a href="https://peps.python.org/pep-0783/">PEP 783 – Emscripten Packaging | peps.python.org</a></li>
<li><a href="https://discuss.python.org/t/pep-783-emscripten-packaging-is-accepted/107393">PEP 783 – Emscripten Packaging is accepted - WebAssembly - Discussions on Python.org</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (item 48462759) was highly positive, with many users expressing excitement about the reduced maintenance burden and the potential for more Python packages in the browser. Some commenters noted the importance of PEP 783 and the long-awaited nature of this feature.

**Tags**: `#Pyodide`, `#WASM`, `#Python`, `#PyPI`, `#WebAssembly`

---

<a id="item-2"></a>
## [Honda Civic Infotainment Vulnerable via AOSP Test Keys](https://juniperspring.org/posts/honda-evil-valet/) ⭐️ 8.0/10

Honda uses publicly-known AOSP test keys to sign firmware updates for 10th-gen Civic infotainment systems, allowing arbitrary code execution via USB with physical access. This vulnerability undermines the security of millions of vehicles, as physical access to the USB port enables full compromise of the head unit, which may have access to sensitive sensors like microphones and GPS. The updates are Android 4.2.2 recovery packages with Honda-added version checks that can be spoofed; the signing key is the default AOSP test key, publicly available on GitHub.

hackernews · librick · Jun 14, 00:49 · [Discussion](https://news.ycombinator.com/item?id=48523080)

**Background**: AOSP test keys are default signing keys included in the Android Open Source Project for development purposes. They are not meant for production use, but some manufacturers inadvertently ship products using these keys, allowing anyone with the public key to sign and flash custom code.

<details><summary>References</summary>
<ul>
<li><a href="https://juniperspring.org/posts/honda-evil-valet/">Honda Civics and the Evil Valet | Juniperspring</a></li>
<li><a href="https://github.com/wfairclough/android_aosp_keys">GitHub - wfairclough/android_aosp_keys: The platform keys that are used as test keys for the AOSP build · GitHub</a></li>
<li><a href="https://github.com/maks/aosp-signapk/blob/master/aosp_test_keys/testkey.pk8">aosp-signapk/aosp_test_keys/testkey.pk8 at master · maks/aosp-signapk</a></li>

</ul>
</details>

**Discussion**: Commenters debated the real-world risk, with some arguing that physical access already allows simpler attacks like hiding a spy device, while others praised Honda's openness compared to other manufacturers. The discussion also highlighted broader automotive security concerns and the importance of signature verification.

**Tags**: `#automotive security`, `#reverse engineering`, `#infotainment`, `#Android`, `#Honda`

---

<a id="item-3"></a>
## [GLM 5.2 Fully Open Frontier Model Released by Z.ai](https://twitter.com/jietang/status/2065784751345287314) ⭐️ 8.0/10

Z.ai released GLM 5.2, a fully open frontier AI model with a 1-million-token context window and enhanced coding capabilities, available immediately on all GLM Coding Plan tiers. This release provides a permissively licensed, open alternative to restricted US frontier models, potentially lowering costs and democratizing access to advanced AI for developers worldwide. GLM 5.2 supports a usable 1M-token context window and introduces two new thinking-effort levels, with API access and chatbot available alongside the open model.

hackernews · aloknnikhil · Jun 13, 16:18 · [Discussion](https://news.ycombinator.com/item?id=48518684)

**Background**: Frontier AI models are the most advanced general-purpose models, typically trained with enormous computational resources and capable of exceeding state-of-the-art across multiple domains. Z.ai (formerly Zhipu AI) is a Chinese AI company that develops the GLM series of models. The release comes amid increasing restrictions on US frontier models, highlighting the geopolitical dimension of AI development.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.z.ai/devpack/latest-model">How to Switch Models - Overview - Z.AI DEVELOPER DOCUMENT</a></li>
<li><a href="https://www.buildfastwithai.com/blogs/glm-5-2-review-2026">GLM-5.2 Review 2026: Z.ai's 1M-Context AI Model</a></li>
<li><a href="https://en.wikipedia.org/wiki/Z.ai">Z.ai - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community comments express gratitude for Chinese labs' openness, with some noting the model may be about half a year behind leading US models but could still disrupt pricing. Others highlight the contrast between Chinese open releases and US censorship, and look forward to seeing how the model changes workflows.

**Tags**: `#AI`, `#open-source`, `#large language model`, `#GLM`, `#frontier model`

---

<a id="item-4"></a>
## [Census Bureau Bans Noise Infusion in Statistical Products](https://desfontain.es/blog/banning-noise.html) ⭐️ 8.0/10

The U.S. Census Bureau has banned the use of noise infusion, a differential privacy technique, in its statistical products, removing a key privacy protection from published data. This policy change undermines trust in government data collection and increases the risk of re-identifying individuals from census data, potentially affecting privacy for all U.S. residents. Noise infusion adds random noise to data to prevent reconstruction attacks; its removal makes it easier for malicious actors to recover individual responses from aggregated statistics.

hackernews · nl · Jun 13, 13:54 · [Discussion](https://news.ycombinator.com/item?id=48517377)

**Background**: Differential privacy is a mathematical framework that limits what can be inferred about individuals from statistical releases. The Census Bureau had used noise infusion to protect respondent confidentiality in recent censuses, but critics argued it reduced data accuracy for research and policy-making.

**Discussion**: Commenters expressed concern that the ban erodes trust and enables weaponization of sensitive data. Some argued that good institutions require granular data for effective policy, while others emphasized the necessity of differential privacy to prevent scams and fraud.

**Tags**: `#privacy`, `#census`, `#differential privacy`, `#data policy`, `#statistics`

---

<a id="item-5"></a>
## [New Pancreatic Cancer Drug Doubles Survival](https://economist.com/science-and-technology/2026/06/12/treating-pancreatic-tumours-may-have-revealed-cancers-master-switch) ⭐️ 8.0/10

A new daily pill, daraxonrasib, targeting the KRAS mutation, doubled survival time in a phase 3 trial of 500 patients with metastatic pancreatic cancer, with fewer side effects than chemotherapy. This breakthrough offers hope for pancreatic cancer, one of the deadliest cancers with a five-year survival rate of only 12%, and demonstrates that previously 'undruggable' targets like KRAS can be effectively treated, potentially opening doors for other hard-to-treat cancers. The trial results were presented at the American Society of Clinical Oncology (ASCO) annual meeting in Chicago in May 2026. The drug is a KRAS G12D inhibitor, specifically targeting the mutation found in about 40% of pancreatic cancer cases.

hackernews · andsoitis · Jun 13, 13:34 · [Discussion](https://news.ycombinator.com/item?id=48517199)

**Background**: KRAS is a gene that, when mutated, drives uncontrolled cell growth in many cancers. For decades, it was considered 'undruggable' because its smooth surface lacked deep pockets for drug binding. Recent advances in drug design, such as targeted covalent inhibitors, have enabled the development of drugs like daraxonrasib that can block mutant KRAS.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/society/2026/may/31/daily-pill-daraxonrasib-double-survival-time-pancreatic-pancreas-cancer-clinical-trial">Daily pill can double survival time for world’s deadliest cancer , trial ...</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted the significance of targeting KRAS, previously considered undruggable, and expressed hope for broader applications. Some also emphasized the need for better early detection and warned about threats to US science funding.

**Tags**: `#biomedical research`, `#cancer treatment`, `#KRAS`, `#drug development`, `#clinical trial`

---

<a id="item-6"></a>
## [Phoenix LiveView 1.2 Released](https://phoenixframework.org/blog/phoenix-liveview-1-2-released) ⭐️ 8.0/10

Phoenix LiveView 1.2 has been released, introducing new features and improvements to the real-time web framework for Elixir. This release strengthens Phoenix LiveView's position as a leading framework for building real-time, server-rendered applications without complex client-side JavaScript, appealing to developers seeking simplicity and performance. The release includes enhancements to LiveView's streaming, error handling, and integration with Phoenix's broader ecosystem, though specific changelog details were not provided in the summary.

hackernews · ksec · Jun 14, 04:53 · [Discussion](https://news.ycombinator.com/item?id=48524293)

**Background**: Phoenix LiveView is a library for the Phoenix web framework (written in Elixir) that enables rich, real-time user experiences with server-rendered HTML. It leverages Elixir's concurrency and fault-tolerance on the BEAM virtual machine to handle WebSocket connections and state synchronization efficiently.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Elixir_(programming_language)">Elixir (programming language)</a></li>

</ul>
</details>

**Discussion**: Community comments express strong enthusiasm for Phoenix and LiveView, with users praising its simplicity and performance compared to JavaScript-heavy frameworks like Next.js. Some users discuss using LiveView for side projects and compare it to ASP.NET/Blazor, while others note the potential of LLMs for writing Elixir code.

**Tags**: `#Phoenix`, `#LiveView`, `#Elixir`, `#web development`, `#framework release`

---

<a id="item-7"></a>
## [Amazon CEO's Talks Led to U.S. Crackdown on Anthropic AI](https://www.wsj.com/tech/ai/amazon-ceos-talks-with-u-s-officials-triggered-crackdown-on-anthropic-models-dcc90578?st=Yct6gx&reflink=desktopwebshare_permalink) ⭐️ 8.0/10

The Wall Street Journal reported that Amazon CEO Andy Jassy's discussions with U.S. officials triggered a government crackdown on Anthropic's AI models, raising concerns about regulatory motives and corporate influence. This story highlights the complex interplay between big tech companies and AI regulation, potentially setting a precedent for how corporate interests can shape government actions on AI safety. Anthropic is a leading AI safety company, and Amazon has invested heavily in it, including a $4 billion partnership. The specific technical reasons for the crackdown remain unclear, but the community notes that all LLMs are vulnerable to jailbreaking.

hackernews · ls612 · Jun 13, 16:57 · [Discussion](https://news.ycombinator.com/item?id=48519092)

**Background**: Anthropic is known for its Claude models, which emphasize safety and alignment. The company has received significant investment from Amazon, raising questions about conflicts of interest when Amazon's CEO discusses competitors with regulators.

**Discussion**: Commenters debated whether the crackdown was justified, with some noting that all LLMs can be jailbroken and questioning the government's motives. Others pointed to Amazon's investment in Anthropic and suggested the action might be politically motivated rather than based on technical merit.

**Tags**: `#AI regulation`, `#Anthropic`, `#Amazon`, `#government oversight`, `#AI safety`

---

<a id="item-8"></a>
## [Running DOS on Behringer DDX3216 with Custom BIOS](https://chrisdevblog.com/2026/06/08/running-dos-on-behringers-ddx3216-using-a-diy-x86-bios/) ⭐️ 8.0/10

A developer reverse-engineered the Behringer DDX3216 digital mixer and built a custom x86 BIOS from scratch, enabling it to run DOS. The project demonstrates full boot-up to a DOS prompt with keyboard input and screen output. This project showcases deep reverse-engineering of a proprietary embedded system, proving that even specialized hardware can be repurposed for retro computing. It highlights the potential for open-source firmware in legacy audio equipment. The custom BIOS was written entirely in assembly and C, requiring reverse-engineering of the mixer's hardware, including its display, keyboard, and memory map. The developer used AI to generate a font file for the BIOS, though manual fixes were needed for pixel errors.

hackernews · rasz · Jun 13, 18:32 · [Discussion](https://news.ycombinator.com/item?id=48520080)

**Background**: The Behringer DDX3216 is a digital mixer released in 2002, originally running proprietary firmware. DOS is a legacy operating system that requires a BIOS to initialize hardware and load the OS. Building a custom BIOS involves understanding the x86 architecture and the specific hardware interfaces of the target device.

**Discussion**: Commenters praised the project's technical depth and offered suggestions, such as using far pointers in C to simplify memory access. Some noted the historical context of DOS-compatible machines and compared this work to similar projects on newer Behringer mixers.

**Tags**: `#reverse engineering`, `#x86`, `#BIOS`, `#embedded systems`, `#retro computing`

---

<a id="item-9"></a>
## [Large Context Windows in LLMs Are Unreliable](https://garrit.xyz/posts/2026-05-06-dont-trust-large-context-windows) ⭐️ 7.0/10

A blog post argues that large context windows in large language models (LLMs) suffer from performance degradation, with the model losing focus on relevant information as context grows. The author warns developers not to trust these windows for critical tasks. This critique challenges the common assumption that larger context windows always improve LLM performance, which is crucial for developers building reliable AI applications. The debate highlights the need for better context management strategies. The post notes that performance degradation becomes noticeable beyond 100k tokens, with issues like lost focus and increased hallucination. Some users report acceptable performance up to 800k tokens with certain models like Opus, but results vary.

hackernews · computersuck · Jun 14, 06:07 · [Discussion](https://news.ycombinator.com/item?id=48524620)

**Background**: Large language models process text in chunks called tokens, and the context window is the maximum number of tokens the model can consider at once. Larger windows allow the model to handle longer documents or conversations, but they can also dilute the model's attention, leading to poorer performance on specific tasks.

**Discussion**: Commenters share mixed experiences: some find large windows work well with careful design (e.g., recursive agent loops), while others echo the author's concerns. A common theme is that irrelevant context harms performance, and memory systems often make models dumber.

**Tags**: `#LLM`, `#context window`, `#AI reliability`, `#software engineering`

---

<a id="item-10"></a>
## [Mapping SQLite Result Columns to Source Tables](https://simonwillison.net/2026/Jun/13/sqlite-column-provenance/#atom-everything) ⭐️ 7.0/10

Simon Willison explored programmatically identifying the source table.column for each result column in SQL queries, using Claude Code to find solutions for enhancing Datasette's query rendering. This capability would allow Datasette to render SQL query results with additional metadata about column provenance, improving data exploration and debugging. The investigation also demonstrates the practical use of AI-assisted development for solving real-world database problems. Claude Code (Opus 4.8) identified three promising approaches: using the apsw library, using ctypes to access SQLite's sqlite3_column_table_name() C function, and analyzing the output of EXPLAIN. The sqlite3_column_table_name() function is not exposed in Python's standard sqlite3 module.

rss · Simon Willison · Jun 13, 23:05

**Background**: Datasette is an open-source tool for exploring and publishing relational databases. When executing arbitrary SQL queries, it currently lacks the ability to show which source table each result column originates from, especially when joins or CTEs are involved. The SQLite C API provides a function sqlite3_column_table_name() that returns this information, but it is not exposed in Python's built-in sqlite3 module.

**Tags**: `#SQL`, `#Datasette`, `#AI-assisted development`, `#database`, `#query analysis`

---

<a id="item-11"></a>
## [Free Browser-Based SQL to ER Diagram Tool](https://sqltoerdiagram.com/) ⭐️ 6.0/10

A new free tool, sqltoerdiagram.com, converts SQL CREATE statements into entity-relationship diagrams entirely in the browser, with no data uploaded to any server. This tool enhances privacy and convenience for developers who need quick visualizations of database schemas, especially when working with sensitive data. Its excellent mobile usability also makes it accessible on the go. The tool runs entirely client-side using JavaScript, ensuring no data leaves the browser. It supports panning, zooming, and smooth interaction on mobile devices, as noted by users.

hackernews · robhati · Jun 14, 03:43 · [Discussion](https://news.ycombinator.com/item?id=48523992)

**Background**: An entity-relationship (ER) diagram is a visual representation of database entities and their relationships, commonly used in database design. Traditional tools often require installation or upload data to a server, raising privacy concerns. This tool addresses that by processing everything locally.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ER_diagram">ER diagram</a></li>

</ul>
</details>

**Discussion**: Users compared it to existing tools like wwwsqldesigner and explain.dalibo.com, with some praising its mobile UX. One commenter noted that ER diagrams conceptually differ from table diagrams, as SQL alone lacks entity information, but acknowledged the tool's utility. Another requested features like hiding specific connections.

**Tags**: `#SQL`, `#ER diagram`, `#database`, `#tool`, `#privacy`

---

<a id="item-12"></a>
## [Game Boy Workboy Unreleased Addon Recovered](https://tcrf.net/Workboy) ⭐️ 6.0/10

The Game Boy Workboy, an unreleased hardware addon and productivity software suite for the Game Boy, has been recently recovered and documented on TCRF. This recovery adds a rare piece of gaming history, showing Nintendo's early attempt to turn the Game Boy into a productivity device, which appeals to retro computing enthusiasts and preservationists. The Workboy included a keyboard attachment and software for tasks like a calculator, calendar, and address book, but was never commercially released.

hackernews · tosh · Jun 13, 17:43 · [Discussion](https://news.ycombinator.com/item?id=48519552)

**Background**: The Game Boy was a handheld gaming console released by Nintendo in 1989. While primarily for games, some third-party accessories aimed to expand its functionality. The Workboy is one such unreleased accessory that has now been preserved through community effort.

**Discussion**: Community comments express interest in the Workboy's history, with links to a YouTube video providing deeper context. Some commenters also discuss non-gaming apps for modern devices like the Playdate.

**Tags**: `#retro computing`, `#game boy`, `#hardware`, `#preservation`

---

<a id="item-13"></a>
## [luau-wasm 0.1a0: Lua Interpreter for Pyodide](https://simonwillison.net/2026/Jun/13/luau-wasm/#atom-everything) ⭐️ 6.0/10

The initial release of luau-wasm 0.1a0 provides a Lua interpreter compiled to WebAssembly, enabling Lua code execution within Pyodide environments. This release bridges Lua and Python ecosystems in the browser, allowing developers to leverage Lua scripts alongside Python in Pyodide, which could simplify polyglot web applications. The package is published as a WASM wheel on PyPI, making it easy to install via pip in Pyodide. It is based on Luau, a fast, small, and gradually typed Lua implementation from Roblox.

rss · Simon Willison · Jun 13, 23:14

**Background**: Pyodide is a Python distribution for the browser based on WebAssembly, allowing Python code to run in the browser. WebAssembly (WASM) is a binary instruction format that enables high-performance execution of code on web pages. Luau is a derivative of Lua 5.1 with additional features and performance optimizations.

**Tags**: `#lua`, `#webassembly`, `#pyodide`, `#python`

---

